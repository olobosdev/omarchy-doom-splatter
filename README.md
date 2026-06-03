# omarchy-doom-splatter

A Doctor Doom themed setup for [Omarchy](https://omarchy.org) / Hyprland.

**Art by:** [Austin Spencer](https://www.deviantart.com/iamatroymecilike) on DeviantArt

## Palette

| Role | Color |
|------|-------|
| Background | `#050505` |
| Foreground | `#C6D7E0` |
| Accent (gold) | `#F1B100` |
| Cursor (green) | `#00E500` |
| Green dark | `#004500` |
| Cyan | `#0099B7` |
| Red | `#B70000` |

## Features

- ✅ Omarchy color theme
- ✅ Active border: gold → green gradient
- ✅ Window rounding + blur
- ✅ Doom-style animations with bounce
- ✅ Inactive window dim
- ✅ Walker launcher with gold border
- ✅ Waybar with gold clock + green icons
- ✅ Mako notifications with green border

## Installation

### Theme
\`\`\`bash
mkdir -p ~/.config/omarchy/themes/omarchy-doom-splatter/backgrounds
cp colors.toml ~/.config/omarchy/themes/omarchy-doom-splatter/
cp backgrounds/* ~/.config/omarchy/themes/omarchy-doom-splatter/backgrounds/
omarchy-theme-set omarchy-doom-splatter
\`\`\`

### Extras (optional)
\`\`\`bash
cp extras/mako.config ~/.config/mako/config && makoctl reload
cp extras/waybar-style.css ~/.config/waybar/style.css && omarchy-restart-waybar
cp extras/looknfeel.conf ~/.config/hypr/looknfeel.conf && hyprctl reload
\`\`\`

> "Behold! The most arcane powers of the multiverse are mere tools in service of Doom's ambition."

## Icons (optional)

For matching green folder icons, install the Tela icon theme:

```bash
yay -S tela-icon-theme
gsettings set org.gnome.desktop.interface icon-theme "Tela-green-dark"
```

You can also apply it through the GUI with `nwg-look`.
