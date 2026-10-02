<div align="center">

# Paseo-Oxocarbon

**The [Oxocarbon](https://github.com/nyoom-engineering/oxocarbon.nvim) palette as a Paseo theme.**

![#161616](https://img.shields.io/badge/-161616-161616?style=flat-square)
![#393939](https://img.shields.io/badge/-393939-393939?style=flat-square)
![#525252](https://img.shields.io/badge/-525252-525252?style=flat-square)
![#8d8d8d](https://img.shields.io/badge/-8d8d8d-8d8d8d?style=flat-square)
![#f2f4f8](https://img.shields.io/badge/-f2f4f8-f2f4f8?style=flat-square)
![#c693ff](https://img.shields.io/badge/-c693ff-c693ff?style=flat-square)

[![License: MIT](https://img.shields.io/badge/license-MIT-161616?style=flat-square&labelColor=262626)](LICENSE)
[![Paseo](https://img.shields.io/badge/paseo-%E2%89%A50.9.0--beta.1-161616?style=flat-square&labelColor=262626)](https://paseo.sh)

</div>

---

Adds an **Oxocarbon** entry to Paseo's theme picker, so Paseo matches oxocarbon.nvim and Ghostty's `oxocarbon` theme. It uses Paseo's own theme API, so it survives Paseo updates and you can switch away at any time.

## Install

In Paseo, open **Settings > Plugins**, make sure **Enable plugins** is on, paste the source below into **Plugin source** and press **Install plugin**:

```
github:MomePP/Paseo-Oxocarbon
```

Or from a terminal:

```sh
paseo plugin install github:MomePP/Paseo-Oxocarbon
```

Then pick **Oxocarbon** in **Settings > Appearance**.

## Palette

| Token | Colour |
| --- | --- |
| background | `#161616` |
| raised | `#161616` |
| control | `#393939` |
| border | `#393939` |
| ring | `#525252` |
| mutedForeground | `#8d8d8d` |
| foreground | `#f2f4f8` |
| accent | `#c693ff` |

`raised` is set to the background on purpose. Paseo paints it under the whole content pane, and any lift there makes the entire window look brighter. For card separation, set it to `#1b1b1b` (subtle) or `#262626` (clear) in [`index.client.tsx`](index.client.tsx).

## Terminal colours

Paseo themes only cover the app chrome; the terminal's 16 ANSI colours are not part of a theme. [Paseo-Vibrancy](https://github.com/MomePP/Paseo-Vibrancy) applies the matching Oxocarbon ANSI set.

## Uninstall

```sh
paseo plugin remove paseo-oxocarbon
```

## License

[MIT](LICENSE)
