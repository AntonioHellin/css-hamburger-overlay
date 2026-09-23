# css-hamburger-overlay

A pure CSS fullscreen overlay navigation menu featuring smooth hamburger-to-cross transformations, radial scale reveals, and responsive typography without JavaScript.

## Project Overview

`css-hamburger-overlay` is an implementation of a fullscreen mobile-friendly navigation overlay driven entirely by modern CSS transitions and the checkbox hack (`:checked` pseudo-class). It demonstrates how complex UI state and animation choreography can be achieved with zero JavaScript dependencies.

## Features

- **Pure CSS Interaction**: Uses a hidden HTML checkbox toggler with zero JavaScript required.
- **Animated Hamburger Icon**: Smooth rotation and morphing from three horizontal bars into an "X" close icon.
- **Radial Expansion Effect**: Scale and opacity transition revealing the menu overlay radially from the top-left corner.
- **Accessible Hover & Focus Styles**: Clean hover states and transition effects across menu links.
- **Lightweight & Modular**: Isolated styles partitioned between `menu.css` (overlay logic) and `style.css` (landing page layout).

## Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge).

## Installation/Build

No build step or dependencies required.

1. Clone the repository:
   ```bash
   git clone https://github.com/AntonioHellin/hamburger_overlay_menu.git
   cd hamburger_overlay_menu
   ```

2. Serve locally:
   ```bash
   npx serve .
   ```

## Usage

1. Open `index.html` in your web browser.
2. Click the hamburger icon in the top-left corner to trigger the animated fullscreen menu overlay.
3. Click the "X" button to collapse the overlay back into the corner.

## License

This project is licensed under the [MIT License](LICENSE).
