# Oscura Midnight — Void

The super-dark cut of the **Grok Build Oscura Midnight** palette for [Omarchy](https://omarchy.org/). Surfaces drop to true black, and the warm Oscura gold/cream/amber tones are gone: warning, number, and "modified" roles use a muted slate. The ANSI axis stays in the theme's cool families — green and cyan are two separated teal tones, blue and magenta two separated purple tones — each slot spaced in brightness so it reads clearly on the void black.

## Install

```bash
omarchy theme install https://github.com/lajwilson/omarchy-oscura-midnight-theme.git
```

Or *Install → Style → Theme* in the Omarchy menu and paste that URL.

The repo name follows Omarchy’s `omarchy-[name]-theme` convention, so it appears as **Oscura Midnight**.

## Palette

| Token | Hex | Role |
| --- | --- | --- |
| Background | `#000000` | True black void |
| Accent | `#9B7ECE` | Signature purple |
| Lavender | `#C4A7E7` | Bright purple (blue family) |
| Magenta | `#C98FD9` | Purple family (archives) |
| Teal | `#3FB488` | Green family (executables) |
| Cyan | `#5CC9C5` | Cyan family (links) |
| Slate | `#AFA7CC` | Muted neutral (replaces cream/gold) |
| Rose | `#E06C75` | Errors |
| Text | `#D4D4DA` | Primary |

`colors.toml` is the source of truth. Omarchy generates terminal, Neovim, Hyprland, VS Code, and shell configs from it when the theme is applied.

## Background

A single background ships with the theme: the official Omarchy wordmark on the void base. It is applied on `omarchy theme set`.

| File | Resolution | Source |
| --- | --- | --- |
| `omarchy.png` | 3840×2160 | Official Omarchy wordmark on void |

See [CREDITS.md](CREDITS.md) for attribution.

## License

MIT for the theme files.
