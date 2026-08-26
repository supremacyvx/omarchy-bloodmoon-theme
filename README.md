# Omarchy Bloodmoon Theme

A dark, blood-red theme for [Omarchy](https://omarchy.org/), derived from the
[Yamura](https://zed.dev/extensions/yamura) Zed editor theme.

## Install

```bash
omarchy theme install https://github.com/supremacyvx/omarchy-bloodmoon-theme
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
- `fastfetch/config.jsonc` — fastfetch supports true 24-bit color, so every
  section (`green`/`blue`/`magenta` in the stock config) is replaced with the
  theme's accent (`#e06c75` as `38;2;224;108;117`). Copy it to
  `~/.config/fastfetch/config.jsonc`.

## Notes

lazydocker and fastfetch aren't apps Omarchy themes natively, so these two
configs aren't applied automatically by `omarchy theme install` — copy them
in by hand.
