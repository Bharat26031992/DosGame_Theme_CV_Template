# AEgIS: Antihydrogen Gravity Lab

An interactive web-based physics simulator and educational game based on the **AEgIS Experiment** at CERN, where players synthesize antihydrogen and measure its gravitational properties.

## 🎮 About the Project

This project brings the cutting-edge AEgIS (Antimatter Gravity Interaction Study) experiment to life through an engaging, browser-based simulation. Players take on the role of researchers in the AEgIS lab at CERN's Antiproton Decelerator, progressing through four challenging phases of particle physics experimentation.

### Educational Purpose
The game educates players about real antimatter physics, including:
- **Antiproton confinement** in Penning-Malmberg traps
- **Positronium production** via charge-exchange reactions
- **Doppler laser cooling** at extreme frequencies
- **Time-of-flight spectroscopy** for gravitational measurement

## 🎯 Gameplay Features

### Four-Phase Gameplay Loop
1. **Phase 1: Antiproton Capture** - Trap and contain antiprotons using electromagnetic traps
2. **Phase 2: Positronium Production** - Generate Positronium (Ps) atoms by shooting targets
3. **Phase 3: Laser Cooling** - Precisely detune a laser to cool Positronium atoms
4. **Phase 4: Gravity Measurement** - Synthesize antihydrogen and measure gravitational free-fall

### Core Mechanics
- **Resource Management**: Limited particles and time per phase (60 seconds)
- **Precision Tools**: Mouse-based aiming and laser detuning via scroll wheel
- **Dynamic Physics**: Realistic particle collision detection and physics simulation
- **Immersive HUD**: Real-time phase progress, score tracking, and equipment status

### Audio-Visual Experience
- **Retro-CRT Aesthetic**: Green-on-black terminal styling with scan-line effects
- **Procedural Audio**: Dynamic sound synthesis for all game events
- **AI Announcer**: Text-to-speech narration using Web Speech API
- **Scientific Visualization**: Mathematical notation via MathJax for equations and particle symbols

## 🕹️ Controls

| Control | Action |
|---------|--------|
| **W A S D** | Move researcher character |
| **Mouse** | Aim equipment (crosshair cursor) |
| **Left Click** | Activate current equipment |
| **Scroll Wheel** | Adjust laser frequency detuning (Phase 3 only) |
| **Tab** | Open/close interactive lab notebook |

## 📋 Lab Notebook

The in-game notebook provides definitions for key scientific concepts:
- **Penning-Malmberg Trap**: Electromagnetic confinement device
- **Antiproton (p̄)**: Antimatter counterpart to the proton
- **Positronium (Ps)**: Exotic atom of electron + positron
- **Alexandrite Laser Cooling**: Doppler detuning cooling technique
- **Moire Deflectometer**: Apparatus for measuring gravitational deflection

## 🏆 Scoring & Achievements

- **Phase Completion Bonuses**: Time bonuses for rapid progression
- **Achievement Badges**: Unlock special badges for expert performance
- **Leaderboard System**: Save your high scores with custom player IDs
- **Gravity Measurement**: Displays calculated gravitational acceleration (g) based on Time-of-Flight data

## 🛠️ Technical Stack

- **Language**: JavaScript (vanilla, no external game libraries)
- **Rendering**: HTML5 Canvas 2D
- **Physics**: Custom collision detection and particle dynamics
- **Audio**: Web Audio API for procedural sound generation
- **Speech**: Web Speech API for AI announcer
- **Math**: MathJax for rendering scientific notation
- **Fonts**: Google Fonts (Space Mono, VT323)

## 🚀 Getting Started

### Running the Game
1. Clone this repository:
   ```bash
   git clone https://github.com/Bharat26031992/AEgIS_Antihydrogen_4Stage_Game.git
   cd AEgIS_Antihydrogen_4Stage_Game
   ```

2. Open `index.html` in a modern web browser:
   - Chrome/Chromium
   - Firefox
   - Edge
   - Any Chromium-based browser

3. Click **[ENTER LAB]** to start the experiment

### Browser Requirements
- Modern browser with:
  - HTML5 Canvas support
  - Web Audio API support
  - ES6+ JavaScript support
  - Web Speech API (for AI announcer)

## 📁 Project Structure

```
.
├── index.html          # Main game file (HTML + CSS + JavaScript)
└── README.md          # This documentation file
```

The entire game is contained in a single HTML file for easy deployment and accessibility. The file includes:
- **HTML**: Game canvas and overlay screens
- **CSS**: Styling for terminal aesthetic and UI elements
- **JavaScript**: Complete game engine, physics, and audio systems

## 🎓 Educational Value

This project serves as:
- **STEM Outreach Tool**: Makes quantum physics accessible and engaging
- **Physics Visualization**: Illustrates difficult concepts through interactive simulation
- **Code Reference**: Well-commented JavaScript demonstrating:
  - Game state management
  - Collision detection algorithms
  - Audio synthesis techniques
  - Canvas-based graphics rendering

## 🔬 Physics Accuracy

While this is a game, many physics principles are grounded in reality:
- Particle decay and annihilation rates are realistic
- Laser cooling mechanisms follow Doppler cooling principles
- Time-of-flight gravity measurement mimics real apparatus
- Antiproton confinement requirements match Penning trap specifications

## 🐛 Known Features

- Smooth 60 FPS gameplay on modern browsers
- Responsive HUD with real-time updates
- Particle collision detection with physics response
- Procedurally generated hazards per phase
- Score persistence via browser localStorage (optional leaderboard)

## 📝 Game Credits

**Inspired by**: AEgIS Collaboration, CERN Antiproton Decelerator Facility

**Physics Concepts**: Based on publications and resources from:
- The AEgIS experiment at CERN
- CERN's Antiproton Decelerator (AD) program
- Research on antimatter gravity measurements

## 📄 License

This project is designed for educational purposes. Please refer to the repository for specific licensing information.

## 🔗 References

- [AEgIS Experiment](https://aegis.web.cern.ch/)
- [CERN Antiproton Decelerator](https://home.cern/science/accelerators/antiproton-decelerator)
- [Antimatter at CERN](https://home.cern/science/physics/antimatter)

---

**Have fun exploring the fascinating world of antimatter physics!**
