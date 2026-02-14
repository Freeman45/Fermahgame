# ZK Proof Matchmaker - Fermah Game

A fun, educational puzzle game themed around Fermah's universal proof generation marketplace. Match Zero-Knowledge proof requests with the right computational resources!

![Game Preview](https://img.shields.io/badge/Game-Fermah%20Themed-blueviolet)
![Status](https://img.shields.io/badge/Status-Ready%20to%20Deploy-success)

## 🎮 About the Game

**ZK Proof Matchmaker** teaches players about Fermah's core mission - connecting ZK proof generation demand with computational supply (GPUs & FPGAs). 

### Features
- 🎯 **Educational Gameplay**: Learn about different ZK proof types (zkRollups, zkBridges, zkML, zkEVM, etc.)
- 💻 **Hardware Matching**: Match proofs with appropriate compute resources
- 🏆 **Scoring System**: Build streaks and level up
- ⚡ **Progressive Difficulty**: Levels get harder as you advance
- 🌙 **Fermah Themed**: Beautiful gradients and branding inspired by Fermah
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile

### Game Mechanics
1. Select a ZK Proof Request (left column)
2. Select a Compute Resource (right column)  
3. Click "Generate Proof!" to attempt the match
4. Correct matches earn points and increase your streak
5. Complete 3 matches to level up
6. Beat the clock and achieve the highest score!

## 🚀 Deploy to GitHub Pages

### Quick Setup (5 minutes)

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Name it: `fermah-game` (or any name you prefer)
   - Keep it public
   - Don't initialize with README (we have our own)

2. **Upload the game file**
   - Click "uploading an existing file"
   - Drag and drop `fermah-game.html`
   - Rename it to `index.html` (this is important!)
   - Commit the file

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section (left sidebar)
   - Under "Source", select "Deploy from a branch"
   - Select branch: `main` and folder: `/ (root)`
   - Click Save

4. **Access your game**
   - Your game will be live at: `https://yourusername.github.io/fermah-game`
   - It may take 1-2 minutes to deploy

### Alternative: Use Git Command Line

```bash
# Clone your new repository
git clone https://github.com/yourusername/fermah-game.git
cd fermah-game

# Copy the game file and rename it
cp /path/to/fermah-game.html index.html

# Add and commit
git add index.html
git commit -m "Add Fermah ZK Proof Matchmaker game"

# Push to GitHub
git push origin main
```

Then follow step 3 above to enable GitHub Pages.

## 📁 File Structure

```
fermah-game/
├── index.html          # Main game file (rename fermah-game.html to this)
└── README.md          # This file
```

## 🎨 Game Design

### Visual Theme
- **Colors**: Gradient color scheme with teal (#667eea), purple (#764ba2), and pink (#f093fb)
- **Style**: Modern glassmorphism with backdrop blur effects
- **Typography**: Clean sans-serif fonts with gradient text for headings
- **Animations**: Smooth transitions and hover effects

### Educational Elements

The game teaches about:
- **ZK Proof Types**: zkRollups, zkBridges, zkML, zkEVM, Groth16, zkCoprocessors
- **Hardware Requirements**: Understanding what compute resources different proofs need
- **Fermah's Mission**: Making "moon math" (advanced cryptography) accessible to everyone

### Proof Types in Game

| Proof Type | Complexity | Best Hardware |
|------------|------------|---------------|
| zkRollup Batch | High | High-end GPU |
| zkBridge Transaction | Medium | Mid-range GPU |
| zkML Inference | High | High-end GPU |
| zkEVM State Proof | Very High | FPGA |
| Groth16 Verification | Low | Standard GPU |
| zkCoprocessor Query | Medium | Mid-range GPU |

### Compute Resources

| Resource | Type | Performance |
|----------|------|-------------|
| NVIDIA A100 | High-end GPU | 95 TFLOPs |
| NVIDIA RTX 4090 | Mid-range GPU | 82 TFLOPs |
| AMD MI250X | High-end GPU | 90 TFLOPs |
| Intel Stratix 10 | FPGA | Custom Logic |
| NVIDIA RTX 3080 | Standard GPU | 29 TFLOPs |
| AMD RX 7900 XTX | Mid-range GPU | 61 TFLOPs |

## 🔧 Customization

The game is built with vanilla React (loaded via CDN), making it easy to customize:

1. **Adjust Difficulty**: Modify the `timeLeft` initial value (default: 90 seconds)
2. **Change Scoring**: Update the scoring formula in `attemptMatch()`
3. **Add More Levels**: Extend the proof types and resources arrays
4. **Modify Colors**: Update the CSS gradient values
5. **Add Sound Effects**: Include audio files and play on actions

## 🌟 About Fermah

Fermah is the universal proof generation layer, functioning as a marketplace where:
- **Supply Side**: GPUs and FPGAs provide computational power
- **Demand Side**: Projects need ZK proofs for rollups, bridges, coprocessors, etc.
- **Matchmaker**: Connects supply and demand efficiently

Learn more at [fermah.xyz](https://fermah.xyz)

## 📝 Technical Details

- **Framework**: React 18 (via CDN)
- **Styling**: Vanilla CSS with modern effects
- **Deployment**: Static HTML - no build process needed
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance**: Lightweight - loads in < 1 second

## 🎯 Game Strategy Tips

1. **Match by Complexity**: 
   - Very High → FPGA
   - High → High-end GPU
   - Medium → Mid-range GPU
   - Low → Standard GPU

2. **Build Streaks**: Consecutive correct matches multiply your score!

3. **Time Management**: You get +30 seconds per level, but don't waste time

4. **Think Fast**: Each level requires 3 matches, plan your moves

## 📜 License

This game is created as an educational project inspired by Fermah's technology. Feel free to fork, modify, and share!

## 🤝 Contributing

Want to improve the game? Ideas:
- Add more proof types and hardware
- Implement difficulty settings
- Add sound effects and music
- Create a leaderboard system
- Add animations for successful matches
- Mobile-optimized controls

## 📧 Contact

For questions about Fermah: [fermah.xyz](https://fermah.xyz)

---

**Made with 💜 for the Fermah community**

*Bringing Moon Math to the Masses* 🌙
