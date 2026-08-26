# Omarchy Bloodmoon Theme

A dark, blood-red theme for [Omarchy](https://omarchy.org/), derived from the
[Yamura](https://zed.dev/extensions/yamura) Zed editor theme.

## Install

```bash
omarchy theme install https://github.com/<your-username>/omarchy-bloodmoon-theme
```

## What's Included

- `colors.toml` — the core palette, derived from Yamura Dark. Themes Hyprland,
  the Omarchy shell, Alacritty/Foot/Ghostty/Kitty, btop, Chromium, Neovim,
  Helix, VSCode, Obsidian, and Claude Code automatically.
- `icons.theme` — `Yaru-red-dark` to match the accent.
- `btop.theme` — a hand-tuned monochrome-red override (the auto-generated
  version leaned too purple/green for this theme's taste).
- `backgrounds/` — `bg1.jpg`, `bg2.png`.
- `lazydocker/config.yml` — lazydocker only supports the 8 named ANSI colors
  (no hex), so this sets `red`/`bold` for borders and highlights. Since it
  references the named color rather than a hex value, it automatically
  matches whichever theme's red is active in your terminal. Copy it to
  `~/.config/lazydocker/config.yml`.

## Notes

lazydocker isn't one of the apps Omarchy themes natively, so its config isn't
applied automatically by `omarchy theme install` — copy it in by hand.
