# Cyber Bird 🐦

A cyberpunk-themed Flappy Bird game with neon visuals, smooth animations, and customizable gameplay. Fly through the neon cityscape and avoid obstacles in this retro-futuristic adventure!

![Cyber Bird](https://img.shields.io/badge/Game-Cyber%20Bird-00f5ff?style=for-the-badge&logo=gamepad)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🎮 Features

### Core Gameplay
- **Classic Flappy Bird Mechanics**: Navigate through obstacles by timing your jumps perfectly
- **Lives System**: Start with multiple lives (configurable 1-10)
- **Ghost Mode**: When you lose a life (but have more remaining), enter ghost mode for temporary invincibility
- **Score System**: Track your score and compete for high scores
- **High Score Persistence**: Your high score is saved locally

### Visual Features
- **Cyberpunk Aesthetic**: Neon blue and orange color scheme with glowing effects
- **Parallax Scrolling**: Dynamic background with animated stars
- **Animated Bird**: 
  - Smooth wing flapping animation
  - Random blinking animation for personality
  - Rotation based on velocity
- **Textured Ground**: Scrolling chevron pattern with parallax effect
- **Glowing Pipes**: Neon obstacles with grid patterns and color-coded caps
- **Visual Effects**: Glitch effects, shadows, and smooth transitions

### Customization
- **Adjustable Difficulty**: Customize pipe spacing, gap size, and speed
- **Lives Configuration**: Set the number of lives (1-10)
- **Ghost Duration**: Adjust how long ghost mode lasts (500-5000ms)
- **Toggle Pipes**: Enable or disable obstacles for practice mode
- **Reset Options**: Reset individual settings or all settings to defaults

### Controls
- **Spacebar** or **Click/Tap**: Make the bird fly up
- **Enter**: Pause/Resume the game
- **Two-Finger Tap** (Mobile): Pause/Resume
- **Menu Button**: Access settings and how-to-play guide
- **Restart Button**: Restart the current game
- **Sound Toggle**: Enable/disable sound effects

## 🎯 How to Play

1. **Start the Game**: Click or tap to begin, or press Spacebar
2. **Navigate**: Keep the bird flying by pressing Spacebar or clicking/tapping
3. **Avoid Obstacles**: Fly through the gaps between pipes
4. **Score Points**: Each pipe you pass gives you one point
5. **Survive**: Don't hit the pipes or the ground!

### Tips
- Don't fly too high or too low
- Time your jumps carefully
- Use ghost mode strategically when you have multiple lives
- Practice makes perfect!

## ⚙️ Settings

Access the settings menu to customize your gameplay experience:

- **Enable Pipes**: Toggle obstacles on/off
- **Pipe Spacing** (150-500px): Distance between pipes
- **Pipe Gap** (100-300px): Size of the gap between top and bottom pipes
- **Pipe Speed** (1-10 px/frame): How fast pipes move
- **Lives** (1-10): Number of lives you start with
- **Ghost Duration** (500-5000ms): How long ghost mode lasts

All settings are saved automatically and persist between sessions.

## 🚀 Getting Started

### Installation

No installation required! This is a single-file HTML5 game that runs entirely in your browser.

1. Clone or download this repository
2. Open `Index.html` in any modern web browser
3. Start playing!

### Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- No additional dependencies or build process needed

### Mobile Support

The game is fully responsive and optimized for mobile devices:
- Touch controls for tap-to-fly
- Two-finger tap to pause
- Responsive canvas sizing
- Mobile-friendly UI

## 🎨 Technical Details

### Technologies Used
- **HTML5 Canvas**: For rendering game graphics
- **Vanilla JavaScript**: No frameworks required
- **CSS3**: Styling and animations
- **Web Audio API**: Sound effects
- **LocalStorage**: Save settings and high scores

### Performance Optimizations
- Offscreen canvas caching for ground patterns
- Frame-rate independent movement using delta time
- Efficient collision detection
- Optimized rendering pipeline

### Browser Compatibility
- Chrome/Edge (Recommended)
- Firefox
- Safari
- Opera

## 📝 Game States

- **Paused**: Game is paused, can be resumed
- **Playing**: Active gameplay
- **Falling**: Bird is falling after losing last life
- **Game Over**: Game has ended, can restart

## 🎵 Sound Effects

The game includes sound effects for:
- Wing flapping
- Scoring points
- Collisions/crashes
- Game reboot/restart

Sound can be toggled on/off via the sound button in the top controls.

## 🏆 Scoring

- **Points**: Earn 1 point for each pipe you successfully pass
- **High Score**: Your best score is automatically saved
- **Reset**: High score can be reset from the settings menu

## 🐛 Known Features

- Random blinking animation adds personality to the bird
- Smooth parallax scrolling creates depth
- Ghost mode provides a second chance when you have multiple lives
- Pipes become transparent when hit for better visibility
- Game over screen shows your final score with a subtle overlay

## 📄 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 🙏 Acknowledgments

- Inspired by the classic Flappy Bird game
- Built with modern web technologies
- Cyberpunk aesthetic inspired by retro-futuristic design

---

**Enjoy flying through the neon cityscape!** ✨

