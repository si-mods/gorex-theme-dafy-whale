# Dafy Whale

A blue ocean theme for [GoRex](https://github.com/si-mods/gorex), in light and dark. It is a port of the web theme [dafy-whale-theme](https://github.com/DViridescent/dafy-whale-theme).

It has:

- an ocean palette for the window (the 31 GoRex seeds, light and dark),
- the terminal colors "Nord Light" and "Night Owl" (used when you have not set `terminal.theme`),
- soft sea-surface glows in the window background,
- a faint watermark at the bottom right: a drawing of a whale-girl character (see "The images"),
- a brand row in the sidebar: a whale icon and the wordmark "Dafy Whale".

## The images

- `assets/whale_side.png` and `assets/whale_front.png` are a drawing of a whale-girl character (in the upstream project, 鲸鱼娘立绘, MIT). They are not a picture of a whale. `whale_side.png` is the watermark. `whale_front.png` is for the mascot of later GoRex versions.
- `assets/fish_idle.png` and `assets/fish_happy.png` are fish images for the moving layers and the mascot of later GoRex versions (see `docs/DSK-010-theme-ambience.md` in the GoRex repo). A GoRex build that does not draw them ignores them.
- `assets/logo.svg` is the whale icon in the sidebar's brand row.

The watermark shows only when the glass setting is on. With glass off, the terminal card is opaque and covers it, so you see it in the sidebar and the gaps only. In light mode it is quite visible through a translucent terminal. The manifest has one opacity (0.10) for both appearances; GoRex does not yet take an opacity for each appearance.

## Install

```
gorex pack install dafy-whale
```

Then set `"appearance.theme": "dafy-whale"` in `settings.json`, or use the theme on the Extensions page.

## Licenses

The pack's own work is MIT (`LICENSE`). The images come from other projects with their own licenses. Read `NOTICE`, `LICENSE-whale.txt` and `LICENSE-fish.txt` before you reuse them. The fish images are modified (scaled down) copies.
