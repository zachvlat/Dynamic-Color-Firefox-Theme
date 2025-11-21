# 🌌 COSMIC Firefox Theme

*A custom `userChrome.css` theme inspired by System76’s COSMIC desktop.*

This theme brings COSMIC-style roundness, dark surfaces, and accent colors to Firefox. It modifies tabs, toolbars, the URL bar, bookmarks bar, menus, and general chrome elements for a cohesive COSMIC look.

## ✨ Features

* Global roundness control (`--cosmic-radius`)
* Global accent color (`--cosmic-accent`)
* COSMIC-style dark UI surfaces
* Rounded tabs with accent-colored selection
* Rounded and highlighted URL/search bar
* Styled bookmarks toolbar and menus
* Consistent rounded elements across popups, panels, buttons
* Optional cleaner look by hiding the title bar

## 🎨 Customization

You can adjust the theme by editing the variables at the top of `userChrome.css`:

```css
--cosmic-radius: 22px;    /* Adjust UI roundness */
--cosmic-accent: #4a86cf; /* Accent color */
--cosmic-bg: #2b2b2b;     /* Main background color */
```

## 📦 Installation

1. Go to **about:config**

   * Set: `toolkit.legacyUserProfileCustomizations.stylesheets` → **true**
2. Open your Firefox profile folder:
   **Menu → Help → More Troubleshooting Information → Profile Folder**
3. Create a `chrome` folder inside the profile if it doesn’t exist.
4. Place the `userChrome.css` file in the `chrome` folder.
5. Restart Firefox.

## 🖼️ Preview
