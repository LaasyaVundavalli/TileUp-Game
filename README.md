# Stack Game

An upgraded 3D block stacking game built with Three.js and GSAP. Stack blocks as high as possible by placing them precisely on top of each other. Miss the placement and the game ends!

## Features

### 🎮 Core Gameplay
- **3D Block Stacking**: Place moving blocks on top of each other to build a tower
- **Precision Required**: Blocks must overlap sufficiently to stay on the stack
- **Progressive Difficulty**: Each level adds a new moving block
- **Score Tracking**: Your score increases with each successful placement

### 🎨 UI/UX Enhancements
- **Modern Design**: Clean layout with Poppins font
- **Dark/Light Mode**: Toggle between themes with smooth transitions (default: dark)
- **Smooth Animations**: GSAP-powered transitions and effects
- **Responsive Design**: Optimized for desktop and mobile
- **Visual Feedback**: Falling animations for missed blocks

### 🎯 Game States
- **Ready**: Start screen with play button
- **Playing**: Active gameplay with moving blocks
- **Game Over**: End screen with restart option
- **Resetting**: Animated cleanup between games

## How to Play

1. **Start**: Click the "Start" button or press Spacebar
2. **Place Blocks**: Click or press Spacebar when the moving block is aligned
3. **Build Tower**: Successfully placed blocks stay, building your stack
4. **Game Over**: If you miss placement, the game ends
5. **Restart**: Click or press Spacebar to play again

## Controls

- **Mouse Click**: Place block
- **Spacebar**: Place block
- **Theme Toggle**: Click the moon/sun icon in the top-right

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties and animations
- **Vanilla JavaScript**: Game logic and interactions
- **Three.js**: 3D rendering and graphics
- **GSAP**: Smooth animations and transitions

## Browser Support

Requires WebGL support. Works in all modern browsers including Chrome, Firefox, Safari, and Edge.

## File Structure

```
├── index.html      # Main HTML structure
├── style.css       # Styling and theme management
├── script.js       # Game logic, Three.js setup, and theme toggle
└── README.md       # This file
```

## Getting Started

Simply open `index.html` in any modern web browser with WebGL support. No server or build process required.

## Customization

- **Colors**: Modify CSS custom properties in `:root` and `.light-mode`
- **Block Colors**: Adjust color generation in the `Block` class constructor
- **Game Speed**: Change `speed` and `MOVE_AMOUNT` in the `Block` class
- **Camera**: Modify camera settings in the `Stage` class

## Credits

Original game concept and Three.js implementation inspired by classic stacking games.

## License

This project is open source and available under the MIT License.