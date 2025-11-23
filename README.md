# Dynamic Color Firefox Theme

A minimal Firefox theme that dynamically colors the interface using CSS custom properties while maintaining the browser's default layout and behavior.

## Installation

1. Go to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`
2. Find your profile folder via `about:profiles`
3. Create a `chrome` folder in your profile directory
4. Save `userChrome.css` in the chrome folder
5. Restart Firefox

## Customization

Edit the color variables in the `:root` section of `userChrome.css`:

```css
:root {
  --accent-color: AccentColor;
  --accent-mixed: color-mix(in srgb, AccentColor 20%, black);
  --canvas-text: CanvasText;
  --canvas: Canvas;
}
