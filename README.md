# 🎮 Sabbir Boss Game

A fun and addictive web-based clicker game where you defend **Sabbir** (the best teacher of MISC!) from swarms of mosquitoes! Click fast, build combos, and survive the waves.

![Sabbir Boss Game](https://img.shields.io/badge/Game-Active-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🎯 Objective

Protect Sabbir from mosquitoes before they swarm him! Click incoming mosquitoes to eliminate them, maintain combos for bonus points, and survive increasingly difficult waves.

## ✨ Features

- **🦟 Realistic Mosquitoes** - Detailed animations with flapping wings and natural hovering
- **😊 Dynamic Expressions** - Sabbir switches from happy to angry as mosquitoes approach
- **🔥 Combo System** - Build consecutive kills for multiplied bonus points
- **📈 Progressive Difficulty** - Waves escalate with more mosquitoes spawning faster
- **🎵 Music Control** - Toggle background music with one click
- **💥 Splat Effects** - Satisfying visual feedback when eliminating pests
- **📱 Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- **🌈 Beautiful UI** - Gradient backgrounds, glowing elements, and smooth animations
- **⚡ No Dependencies** - Pure vanilla JavaScript, HTML5, and CSS3

## 🕹️ How to Play

1. **Open** `index.html` in your web browser
2. **Click** on mosquitoes to eliminate them before they reach Sabbir
3. **Build Combos** - Kill mosquitoes quickly to earn multiplied points
4. **Survive Waves** - Each wave brings more mosquitoes and increases difficulty
5. **Game Over** - When 10 mosquitoes reach Sabbir's face, it's game over
6. **Restart** - Click "PLAY AGAIN" to restart and beat your high score

## 🎮 Game Mechanics

| Mechanic | Value |
|----------|-------|
| Base Points (per mosquito) | 10 pts |
| Combo Bonus | 5 pts × combo multiplier |
| Game Over Condition | 10 mosquitoes on face |
| Wave Progression | Increases every 10 spawns |
| Max Speed Increase | 50% faster at Wave 10+ |

### Score Breakdown

- **Wave 1-2**: 3 mosquitoes per spawn
- **Wave 3-4**: 4 mosquitoes per spawn
- **Wave 5-6**: 5-6 mosquitoes per spawn
- **Wave 7-9**: 6-8 mosquitoes per spawn
- **Wave 10+**: 8-11 mosquitoes per spawn

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or dependencies required

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sabbir-boss-game.git
   cd sabbir-boss-game
   ```

2. **Customize Images** (Optional)
   - Replace `happy-sabbir.png` with your own happy Sabbir image
   - Replace `angry-sabbir.png` with your own angry Sabbir image
   - Update image paths in `index.html`

3. **Add Background Music** (Optional)
   - Prepare your music file (MP3 format recommended)
   - Replace `background-music.mp3` with your audio file
   - Update audio path in `index.html`

4. **Open the Game**
   ```bash
   # Simply open the file in your browser
   open index.html
   # Or right-click → Open with Browser
   ```

## 🎨 Customization

### Change Sabbir's Images

In `index.html`, find the image elements and update the `src` attributes:

```html
<img src="happy-sabbir.png" alt="Happy" class="sabbir-image active" id="happyImage">
<img src="angry-sabbir.png" alt="Angry" class="sabbir-image" id="angryImage">
```

### Add Background Music

Replace the audio source in `index.html`:

```html
<audio id="bgMusic" loop>
    <source src="your-music-file.mp3" type="audio/mpeg">
</audio>
```

### Adjust Difficulty

Modify these values in the JavaScript section:

```javascript
const baseDuration = 8000;  // Mosquito flight time (ms)
spawnInterval = setInterval(..., 2500);  // Spawn rate
```

## 🎯 Tips & Tricks

- 💡 **Click Fast** - Build combos early for maximum points
- 👀 **Watch the Face** - Sabbir's expression warns you when mosquitoes are approaching
- 🔔 **Listen for Patterns** - Audio cues help you track incoming waves
- ⏱️ **Focus Zone** - Mosquitoes spawn around Sabbir; concentrate your clicks there
- 🎯 **Prediction** - Anticipate mosquito paths and click ahead of time

## 📱 Browser Support

- ✅ Chrome/Chromium (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Technologies

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure & semantic markup |
| CSS3 | Styling, animations, gradients, responsive design |
| Vanilla JavaScript | Game logic, interactions, animations |

## 📁 Project Structure

```
sabbir-boss-game/
├── index.html              # Main game file
├── happy-sabbir.png        # Happy Sabbir image (replace with your own)
├── angry-sabbir.png        # Angry Sabbir image (replace with your own)
├── background-music.mp3    # Background music (optional)
└── README.md               # This file
```

## 🐛 Known Issues

- Music autoplay may be blocked by some browsers (user interaction required)
- Performance on very old devices may be slower with many simultaneous mosquitoes

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Suggested Improvements

- 🎨 Additional difficulty modes
- 🏆 Leaderboard/high score tracking
- 🎵 Different music tracks
- 👾 Power-ups and special abilities
- 🌙 Dark/Light theme toggle

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created as a fun tribute to Sabbir, the best teacher of MISC!

## 🙏 Credits

- Inspired by classic clicker games
- Built with vanilla web technologies
- Special thanks to everyone at MISC!

## 📞 Support

Have questions or found a bug? Feel free to:

- 🐛 Open an [Issue](https://github.com/yourusername/sabbir-boss-game/issues)
- 💬 Start a [Discussion](https://github.com/yourusername/sabbir-boss-game/discussions)
- 📧 Contact the maintainer

---

**Happy Gaming! 🎮🦟💥**

Made with ❤️ for Sabbir and MISC!
