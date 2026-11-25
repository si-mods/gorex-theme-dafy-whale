# Dafy Whale

A blue ocean theme for [GoRex](https://github.com/si-mods/gorex), in light and dark. It is a port of the web theme [dafy-whale-theme](https://github.com/DViridescent/dafy-whale-theme).

It has:

- an ocean palette for the window (the 31 GoRex seeds, light and dark),
- three sea-surface glows and a whale watermark, drawn by the pack's own background shader (`assets/whale_bg.kage`, a GoRex shader API 2 `background` slot),
- the terminal colors "Nord Light" and "Night Owl" (used when you have not set `terminal.theme`).

The shader needs GoRex v0.62.0 or newer. On an older build the pack still loads as the palette and the terminal colors, with a warning about the shader keys.

## Glow positions, sizes and colors

The shader declares each glow's center, radii and color, and the watermark's opacity, as `//gorex:param` uniforms. `theme.json` sets them to the source theme's values; a fork can tune them in `shaders.background.params` without touching the shader.

## Brand row, mascot and sprites

Earlier versions of this pack had a brand row, a whale mascot and fish sprites, which GoRex's built-in layers drew. GoRex removed those built-in looks (GoRex `docs/DSK-012`): a theme now draws its background with its own shader, and the mascot and sprites are out of scope. The earlier images and their licenses are in the git history (commit `da1d34e`).

## Install

```
gorex pack install dafy-whale
```

Then set `"appearance.theme": "dafy-whale"` in `settings.json`, or use the theme on the Extensions page.

## License

MIT (`LICENSE`). The colors are ported from another project: read `NOTICE`.
