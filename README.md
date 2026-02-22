
# Snacky.js v2

A lightweight, zero-dependency snackbar library with themes, actions, icons, and queue strategies.

## Demo
Live demo: https://your-username.github.io/your-repo/

## Installation

### npm
npm i snacky.js@2

### yarn
yarn add snacky.js@2

### pnpm
pnpm add snacky.js@2

## Quick Usage (Vanilla)
```js
import snacky from "snacky.js";

snacky.show("Hello from Snacky!", { type: "success" });
```
## React Usage
```jsx
import snacky from "snacky.js";

export default function App() {
  return (
    <button onClick={() => snacky.show("React + Snacky!", { type: "info" })}>
      Show Snackbar
    </button>
  );
}
```

## Features
- Theme presets + custom overrides
- Action buttons
- Custom SVG icons
- Queue strategies (stack, replace-oldest, replace-all, collapse)
- Multi-line messages + expand
- Progress bar animation

## Docs
See INSTALLATION.md for full setup and GitHub Pages deployment.

