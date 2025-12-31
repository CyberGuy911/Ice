# 🎮 Mobile Tetris Game

A fully-featured, mobile-optimized Tetris game built with pure HTML5, CSS3, and JavaScript. Play the classic block-stacking puzzle game on any device with smooth touch controls and beautiful animations.

![Tetris Game](https://img.shields.io/badge/Game-Tetris-purple?style=for-the-badge)
![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-green?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-blue?style=for-the-badge)

## ✨ Features

- **🎯 Classic Tetris Gameplay** - All 7 authentic Tetris pieces (tetrominoes)
- **📱 Mobile Optimized** - Responsive design that works perfectly on phones and tablets
- **👆 Touch Controls** - Intuitive swipe gestures and on-screen buttons
- **⌨️ Keyboard Support** - Full desktop keyboard controls
- **🎨 Beautiful UI** - Modern gradient design with smooth animations
- **📊 Scoring System** - Classic Tetris scoring with level progression
- **🔄 Next Piece Preview** - See what's coming next
- **⚡ Progressive Difficulty** - Game speed increases with levels
- **🏆 Statistics Tracking** - Score, level, and lines cleared

## 🚀 Getting Started

### Quick Start

Simply open `tetris.html` in any modern web browser:

1. **Download** the `tetris.html` file
2. **Double-click** to open in your browser
3. **Click START GAME** and play!

No installation, no dependencies, no build process required!

### Online Hosting

You can host this game anywhere that serves HTML files:
- GitHub Pages
- Netlify
- Vercel
- Any web server

## 🎮 How to Play

### Objective

Arrange falling blocks (tetrominoes) to create complete horizontal lines. When a line is completed, it disappears and you earn points. The game ends when blocks stack up to the top of the playing field.

### Controls

#### Mobile / Touch Devices

- **👆 Tap** - Rotate piece clockwise
- **👈 Swipe Left** - Move piece left
- **👉 Swipe Right** - Move piece right
- **👇 Swipe Down** - Move piece down faster
- **🔘 On-Screen Buttons** - Alternative touch controls
  - ↻ Rotate
  - ← ↓ → Directional movement
  - ⬇ HARD DROP - Instantly drop piece to bottom

#### Desktop / Keyboard

- **←** Left Arrow - Move piece left
- **→** Right Arrow - Move piece right
- **↓** Down Arrow - Move piece down faster
- **↑** Up Arrow or **Space** - Rotate piece
- **Enter** - Hard drop (instant drop)

## 🎯 Scoring

| Action | Points |
|--------|--------|
| Single Line | 40 × level |
| Double Lines | 100 × level |
| Triple Lines | 300 × level |
| Tetris (4 Lines) | 1200 × level |
| Hard Drop | 2 points per cell |

### Level Progression

- Start at Level 1
- Advance one level for every 10 lines cleared
- Higher levels increase falling speed
- Maximum challenge at higher levels!

## 🧩 Tetris Pieces

The game includes all 7 classic tetrominoes:

- **I** (Cyan) - The straight piece, perfect for Tetris!
- **O** (Yellow) - The square, stable and simple
- **T** (Purple) - The T-shape, versatile piece
- **S** (Green) - The S-shape, tricky to place
- **Z** (Red) - The Z-shape, mirror of S
- **J** (Blue) - The J-shape, great for corners
- **L** (Orange) - The L-shape, mirror of J

## 🛠️ Technical Details

### Built With

- **HTML5 Canvas** - For smooth graphics rendering
- **CSS3** - Modern styling with gradients and animations
- **Vanilla JavaScript** - No frameworks or libraries needed

### Features Implementation

- **Collision Detection** - Precise piece boundary checking
- **Wall Kicks** - Smart rotation near walls and other pieces
- **Responsive Canvas** - Scales perfectly on any screen size
- **Touch Events** - Native touch gesture support
- **Game Loop** - RequestAnimationFrame for smooth 60 FPS
- **State Management** - Clean game state handling

### Browser Compatibility

Works on all modern browsers:
- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari (iOS and macOS)
- ✅ Samsung Internet
- ✅ Mobile browsers

## 📱 Mobile Optimization

This game is specifically optimized for mobile devices:

- **Responsive Design** - Adapts to any screen size
- **Touch-Friendly** - Large, easy-to-tap buttons
- **No Zoom** - Disabled pinch-to-zoom for better gameplay
- **Portrait Mode** - Perfect for one-handed play
- **Smooth Gestures** - Natural swipe controls
- **Performance** - Optimized for mobile CPUs

## 🎨 Customization

Want to customize the game? Here are some easy tweaks:

### Change Colors

Edit the `COLORS` object in the JavaScript section:
```javascript
const COLORS = {
    I: '#00f0f0',  // Cyan
    J: '#0000f0',  // Blue
    L: '#f0a000',  // Orange
    // ... customize as you like!
};
```

### Adjust Difficulty

Modify the starting speed and level progression:
```javascript
let dropInterval = 1000;  // Starting speed (lower = faster)
level = Math.floor(lines / 10) + 1;  // Change 10 to adjust level-up rate
```

### Resize Board

Change the grid dimensions:
```javascript
const COLS = 10;  // Board width
const ROWS = 20;  // Board height
```

## 🤝 Contributing

Feel free to fork this project and add your own features:
- 🎵 Sound effects and music
- 🎨 Different themes
- 👻 Ghost piece (preview where piece will land)
- 💾 High score persistence
- 🏅 Achievements system
- 🎭 Different game modes

## 📄 License

This project is open source and available for anyone to use, modify, and distribute.

## 🎉 Credits

Created with ❤️ as a demonstration of modern web game development.

Classic Tetris gameplay inspired by the original game created by Alexey Pajitnov.

## 🐛 Known Issues

None currently! If you find a bug, please report it.

## 📞 Support

Having issues? Here are some tips:

- **Game won't start?** Make sure JavaScript is enabled
- **Controls not working?** Try refreshing the page
- **Touch not responsive?** Ensure you're tapping directly on buttons or canvas
- **Slow performance?** Close other browser tabs

---

**Enjoy playing Tetris! 🎮✨**

*Can you beat your high score?*
