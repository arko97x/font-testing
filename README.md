# Font Testing UI

A simple UI for testing fonts in an observability dashboard context. This project allows you to toggle between different fonts to see how they render in a UI similar to modern observability platforms.

## Features

- Left sidebar navigation with placeholder menu items
- Sample graph visualization with dummy data
- Data table with various entry types (normal, warning, info)
- Font switching between IBM Plex Sans and Inter (base size 12px)
- Fully responsive layout using Tailwind CSS

## How to Use

1. Open `index.html` in your browser
2. Use the dropdown in the top-right corner to switch between fonts:
   - IBM Plex Sans
   - Inter

No backend dependencies required - this is a purely client-side application using:
- HTML
- Tailwind CSS (via CDN)
- Vanilla JavaScript

## Development

To modify the UI:
- Edit the HTML structure in `index.html`
- Adjust styling using Tailwind classes
- To add more fonts, update the font imports in the `<head>` section and add new options to the font selector dropdown 