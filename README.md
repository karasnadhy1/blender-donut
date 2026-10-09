# 🍩 Blender Donut

A 3D donut scene modeled, textured, lit, and rendered in Blender, built by following Blender Guru's (Andrew Price) beginner tutorial series. This project was my introduction to the full 3D pipeline: from a default cube to a finished, photorealistic render.

## Final Render

<p align="center">
  <img src="https://raw.githubusercontent.com/karasnadhy1/blender-donut/main/renders/Donut_and_Coffee.png" alt="Final render: pink-iced donut with sprinkles on a plate next to a mug of coffee" width="100%">
</p>

## About

This is my take on the classic Blender Guru donut tutorial. The final scene features a pink-iced donut with mint and pink sprinkles on a plate, next to a mug of coffee, all on a concrete surface. The goal was to learn Blender's core workflow end to end: modeling, sculpting, shading, lighting, and rendering. I followed the tutorial closely, then adjusted colors, composition, and lighting to make the result my own.

**Tutorial:** [Blender Beginner Tutorial (Donut) by Blender Guru](https://www.youtube.com/playlist?list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U)

## What I Learned

- **Modeling:** working with primitives, edit mode, loop cuts, proportional editing, and modifiers (Subdivision Surface, Solidify, Shrinkwrap, Mirror)
- **Sculpting:** shaping organic, uneven forms for a handmade look
- **Icing and sprinkles:** building the icing shape and scattering sprinkles with a particle system
- **Shading:** node-based materials, subsurface scattering, bump and displacement, procedural textures
- **Lighting and camera:** studio-style lighting, depth of field, composition
- **Rendering:** Cycles settings, sampling, denoising, color management
- **Compositing:** post-processing touches like glare and color adjustments

## Project Details

| | |
|---|---|
| **Software** | Blender `[version, e.g. 4.2]` |
| **Render engine** | Cycles |
| **Render time** | `[e.g. ~5 min per frame]` |
| **Resolution** | 1920 × 1080 |
| **Samples** | `[e.g. 256]` |
| **Hardware** | `[CPU / GPU]` |

## Repository Structure

```
blender-donut/
├── donut.blend        # Main Blender project file
├── renders/
│   └── Donut_and_Coffee.png   # Final render
├── textures/          # Any external texture files (if used)
└── README.md
```

## How to Open

1. Install [Blender](https://www.blender.org/download/) (version `[x.x]` or newer recommended).
2. Download or clone this repository:
   ```bash
   git clone https://github.com/karasnadhy1/blender-donut.git
   cd blender-donut
   ```
3. Open `donut.blend` in Blender.
4. To render, switch to the **Render** workspace and press `F12` (still image).

## Challenges and Notes

- `[Something that was hard, e.g. getting the icing to hug the donut shape cleanly]`
- `[Something you changed from the tutorial, e.g. different icing color or sprinkle density]`
- `[What you'd improve next time]`

## Credits

- Tutorial and original design: [Andrew Price (Blender Guru)](https://www.youtube.com/@blenderguru)
- Built with [Blender](https://www.blender.org/)

## License

This project is for learning purposes. The original tutorial belongs to Blender Guru. My own renders and files are shared under the [MIT License](LICENSE) `[or remove this line if you don't add a license]`.
