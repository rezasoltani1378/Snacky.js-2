# Snacky.js

A lightweight, zero-dependency snackbar library with themes, actions, queue strategies, animations, and progress bar.

## Demo
Open `index.html` in a browser.

## Features
- Theme presets + custom overrides
- Action buttons
- Custom SVG icons
- Queue strategies (stack, replace-oldest, replace-all, collapse)
- Multi-line messages + expand
- Progress bar animation

## Usage
```javascript
snacky.show("Hello", { type: "success" });

## Theme
javascript
snacky.show("Glass theme", { theme: "glass" });

## Actions
javascript
snacky.show("Deleted", {
  actions: [{ label: "Undo", onClick: () => alert("Undo") }]
});


---

# ✅ 6) INSTALLATION.md
```markdown
# Installation

## Option 1: Direct Download
1. Download `snacky.js`
2. Include it in your HTML:
```html
<script src="snacky.js"></script>

## Option 2: GitHub Pages Demo
1. Create a new GitHub repository
2. Add all files from this demo
3. Go to **Settings → Pages**
4. Select `main` branch and `/root`
5. Save and wait for deployment

Your demo will be live at:
https://<your-username>.github.io/<repo-name>/


---

# ✅ 7) CHANGELOG.md
```markdown
# Changelog

## 1.2.0
- Themes (dark, light, glass)
- Custom theme overrides
- Action buttons
- Queue strategies
- Custom icons per call
- Expanded animations & progress bar

## 1.1.0
- Improved icons
- Multi-line text wrapping
- Expandable messages
- Better entrance/exit transitions

## 1.0.0
- Initial release
