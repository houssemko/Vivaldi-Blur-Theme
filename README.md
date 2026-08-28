# Vivaldi Blur Theme

A custom CSS theme for Vivaldi browser with glassmorphism/blur effects.

## Installation

1. Enable custom CSS in Vivaldi:
   - Go to `vivaldi://settings/appearance/`
   - Scroll to "Custom UI"
   - Check "Load custom CSS"
   - Select the `custom.css` file from this repository

2. Restart Vivaldi completely (close all windows and reopen)

## Files

- `custom.css` - Main theme file with blur/glass effects
- Variables defined in `:root` for easy customization

## Features

- Glassmorphism/blur effects on toolbars, tabs, popups
- Transparent tab bar with backdrop blur
- Custom styled popups (tab button popup, address bar dropdown, etc.)
- Dark/light theme support via CSS variables
- Hidden search field in tab button popup

## Customization

Edit the CSS variables in `:root` section of `custom.css`:

```css
:root {
    --bgDark: rgba(10, 10, 10, 0.7);
    --bgLight: rgba(255, 255, 255, 0.7);
    --blur: blur(10px);
    --radius: 6px;
    --btnRadius: 6px;
    /* ... more variables */
}
```

## Auto-hide Header

The theme includes `.auto-hide #header { display: none !important; }` for auto-hide header mode.

## License

MIT License - see [LICENSE](LICENSE) for details.