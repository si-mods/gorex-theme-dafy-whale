# Dafy Whale

A blue ocean theme for [GoRex](https://github.com/si-mods/gorex), in light and dark. It is a port of the web theme [dafy-whale-theme](https://github.com/DViridescent/dafy-whale-theme).

It has:

- an ocean palette for the window (the 31 GoRex seeds, light and dark),
- the terminal colors "Nord Light" and "Night Owl" (used when you have not set `terminal.theme`).

## Glows, watermark and brand row

Earlier versions of this pack had sea-surface glows, a whale-girl watermark and a brand row. GoRex removed those built-in looks: a theme now draws its background with its own shader (GoRex `docs/DSK-012`). This version has only the palette and the terminal colors. A later version can draw the glows and the watermark with a theme shader.

The earlier images and their licenses are in the git history (commit `da1d34e`).

## Install

```
gorex pack install dafy-whale
```

Then set `"appearance.theme": "dafy-whale"` in `settings.json`, or use the theme on the Extensions page.

## License

MIT (`LICENSE`). The colors are ported from another project: read `NOTICE`.
