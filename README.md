# Oscura Midnight — Void

The super-dark cut of the **Grok Build Oscura Midnight** palette for [Omarchy](https://omarchy.org/). Surfaces drop to true black, and the warm Oscura gold/cream/amber tones are gone: warning, number, and "modified" roles use a muted slate. The ANSI axis is collapsed as well — green and cyan are one teal family, blue and magenta one purple family — so the whole scheme reads as a single cool gradient of black → purple → lavender.

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
| Magenta | `#B49BE0` | Purple family |
| Teal | `#4FB8A6` | Success and links (green/cyan family) |
| Slate | `#9BA3B0` | Muted neutral (replaces cream/gold) |
| Rose | `#DC5A64` | Errors |
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
