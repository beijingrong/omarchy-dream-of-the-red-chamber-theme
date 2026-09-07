# Dream of the Red Chamber

A pale, warm Omarchy theme inspired by Lin Daiyu in a chrysanthemum garden and
the line from *Dream of the Red Chamber*:

> 孤标傲世携谁隐，一样花开为底迟。

The companion
[`Red Chamber Petals`](https://github.com/beijingrong/omarchy-dream-of-the-red-chamber-petals)
plugin adds restrained blush, rose, and ivory chrysanthemum petals on Wayland's
bottom layer.

## Install

Install the plugin first, then the theme:

```bash
omarchy plugin add https://github.com/beijingrong/omarchy-dream-of-the-red-chamber-petals.git --enable
omarchy theme install https://github.com/beijingrong/omarchy-dream-of-the-red-chamber-theme.git
```

The theme includes a static `red-chamber-petals.toml` opt-in marker. It contains
no scripts, hooks, executables, Lua, terminal commands, or remote resources.

## Remove

Switch to another theme before removal:

```bash
omarchy theme set tokyo-night
omarchy theme remove dream-of-the-red-chamber
```

Remove the companion plugin separately if it is no longer wanted:

```bash
omarchy plugin remove io.github.beijingrong.red-chamber-petals
```

## Contents

- `colors.toml` — the light rose, garden green, and warm paper palette
- `icons.theme` — the icon theme selection
- `backgrounds/grand-view-garden.png` — the static wallpaper and fallback
- `red-chamber-petals.toml` — data-only opt-in marker for the companion plugin

## Artwork provenance

The background illustration was generated and iteratively edited specifically
for this theme under the direction of the repository owner. It is not copied
from the OMatrix project or from another Omarchy theme. *Dream of the Red
Chamber*, first published in the 18th century, is in the public domain; this
illustration is not based on a particular modern film or television adaptation.

The final background is released with this theme under CC BY 4.0. When sharing
it, credit `beijingrong` and link to this repository.

## License

Theme configuration and artwork are licensed under Creative Commons
Attribution 4.0 International. See [LICENSE](LICENSE).
