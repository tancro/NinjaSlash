# Farcade Game Template

A simple template for creating HTML5 games that can be played on Farcade. This template provides a basic setup with Phaser.js and Three.js, making it easy to create 2D and 3D games.

## Features

- 🎮 Pre-configured game container (800x600)
- 🔍 Debug mode (toggle with Alt+D)
- 📦 Common game libraries included:
  - Phaser.js for 2D games
  - Three.js for 3D games
- 🎨 Clean, modern styling
- 📝 Single file setup - just edit index.html

## Getting Started

1. Copy the `index.html` file to your project
2. Open it in your browser to start developing
3. Edit the code in the `<script>` section to build your game

## Development

- The game container is 800x600 pixels by default
- Use Alt+D to toggle debug mode
- All code goes in the single HTML file
- Libraries are loaded from CDN for simplicity

## Game Requirements

Your game should:
- Fit within the 800x600 container
- Handle window resizing gracefully
- Work without requiring external resources
- Be playable with keyboard/mouse controls

## Tips

- Use the debug utilities to log information:
  ```javascript
  debug.log('Your message here')
  ```
- The game container is centered on the page
- Common game libraries are pre-imported and ready to use
- Error handling is built-in
- You can uncomment the Three.js example code to start a 3D game

## Example Code

The template includes:
- Basic Phaser.js setup with physics
- Debug mode toggle
- Error handling
- Three.js setup (commented out)
- Responsive game container

## License

MIT 