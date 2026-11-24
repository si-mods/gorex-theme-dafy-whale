# Dafy Whale

A blue ocean theme for [GoRex](https://github.com/si-mods/gorex), in light and dark. It is a port of the web theme [dafy-whale-theme](https://github.com/DViridescent/dafy-whale-theme).

It has:

- an ocean palette for the window (the 31 GoRex seeds, light and dark),
- the terminal colors "Nord Light" and "Night Owl" (used when you have not set `terminal.theme`),
- soft sea-surface glows in the window background,
- a faint whale watermark at the bottom right,
- a brand row in the sidebar: a whale icon and the wordmark "Dafy Whale".

The pack also carries a front whale and two fish images for the moving layers and the mascot of later GoRex versions (see `docs/DSK-010-theme-ambience.md` in the GoRex repo). A GoRex build that does not draw them ignores them.

## Install

```
gorex pack install dafy-whale
```

Then set `"appearance.theme": "dafy-whale"` in `settings.json`, or use the theme on the Extensions page.

## Licenses

The pack's own work is MIT (`LICENSE`). The images come from other projects with their own licenses. Read `NOTICE`, `LICENSE-whale.txt` and `LICENSE-fish.txt` before you reuse them. The fish images are modified (scaled down) copies.
