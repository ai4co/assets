# AI4CO assets


Simple repository containing assets such as logos, their source files, and other swag!


Some examples - less than 10KB each, simple SVG code that can be [easily modified](https://www.svgviewer.dev/)! 


## Usage

Insert the following in markdown, such as in a `README.md` file:

```markdown
<div align="center">
    <a href="https://github.com/ai4co">
        <img src="https://raw.githubusercontent.com/ai4co/assets/main/svg/ai4co_animated_full.svg" alt="AI4CO Logo" style="width: 40%; height: auto;">
    </a>
</div>
```

to display the below:

<div align="center">
    <a href="https://github.com/ai4co">
        <img src="https://raw.githubusercontent.com/ai4co/assets/main/svg/ai4co_animated_full.svg" alt="AI4CO Logo" style="width: 40%; height: auto;"/>
    </a>
</div>

(remember to adjust `width` and `height` to a suitable value)
You may substitute the `ai4co_animated_full.svg` part at the end of `src` for different icons, such as:

- `ai4co_static.svg`: (note: width set to 15%)

<div align="center">
    <a href="https://github.com/ai4co">
        <img src="https://raw.githubusercontent.com/ai4co/assets/main/svg/ai4co_static.svg" alt="AI4CO Logo" style="width: 15%; height: auto;">
    </a>
</div>

- `ai4co_static_full.svg`:

<div align="center">
    <a href="https://github.com/ai4co">
        <img src="https://raw.githubusercontent.com/ai4co/assets/main/svg/ai4co_static_full.svg" alt="AI4CO Logo" style="width: 40%; height: auto;">
    </a>
</div>


- `ai4co_animated.svg`: (note: width set to 15%)

<div align="center">
    <a href="https://github.com/ai4co">
        <img src="https://raw.githubusercontent.com/ai4co/assets/main/svg/ai4co_animated.svg" alt="AI4CO Logo" style="width: 15%; height: auto;">
    </a>
</div>



## Conversions

To convert from `svg` to `png`, you may use `rsvg-convert`. Install with:

```bash
sudo apt-get install librsvg2-bin
```

Then, convert with:

```bash
rsvg-convert -w 1033 -h 318 svg/rl4co_static_full.svg >  img/rl4co_static_full.png
```

where `1033` and `318` are the width and height of the image, respectively.