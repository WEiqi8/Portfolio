# Stick Figure Fighting Game

![image](https://github.com/user-attachments/assets/68cf6ea6-d5bf-4c21-ade7-4678024488ec)


## 📝 Description

A fun and interactive 2D fighting game featuring animated stick figures. This browser-based game offers a classic two-player experience with punches, kicks, jumps, and health bars, all built using vanilla JavaScript and HTML5 Canvas.

## ✨ Features

- **Two-Player Combat**: Local multiplayer functionality for competitive play
- **Fluid Animations**: Smooth stick figure movements and combat animations
- **Intuitive Controls**: Simple keyboard controls for both players
- **Attack System**: Different attack types with unique hitboxes and damage values
- **Health & Damage**: Visual health bars and hit animations
- **Physics**: Realistic jumping, gravity, and knockback effects
- **Game Over Screen**: Victory announcement with restart functionality

## 🖥️ Technologies Used

- HTML5 Canvas for rendering
- Vanilla JavaScript for game logic
- CSS for UI elements
- Collision detection algorithms
- Animation frame management

## 🎮 Game Controls

**Player 1:**
- Move: A (left) / D (right)
- Jump: Spacebar
- Punch: W
- Kick: S

**Player 2:**
- Move: Arrow Left / Arrow Right
- Jump: 0 (numpad)
- Punch: Arrow Up
- Kick: Arrow Down

## 🚀 Live Demo

[Play the game here](https://yourusername.github.io/stick-figure-fighting-game/)

## 📸 Screenshots

<table>
  <tr>
    <td><img src="https://github.com/yourusername/stick-figure-fighting-game/raw/main/screenshots/gameplay.png" alt="Gameplay" width="300"/></td>
    <td><img src="https://github.com/yourusername/stick-figure-fighting-game/raw/main/screenshots/punch.png" alt="Punch Attack" width="300"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/yourusername/stick-figure-fighting-game/raw/main/screenshots/kick.png" alt="Kick Attack" width="300"/></td>
    <td><img src="https://github.com/yourusername/stick-figure-fighting-game/raw/main/screenshots/gameover.png" alt="Game Over Screen" width="300"/></td>
  </tr>
</table>

## 🛠️ Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stick-figure-fighting-game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd stick-figure-fighting-game
   ```

3. Open `index.html` in your browser to start playing.

## 💻 Code Highlights

- **Object-Oriented Design**: Fighter class encapsulates player behavior and properties
- **Canvas Animation**: Frame-by-frame rendering with requestAnimationFrame
- **Hitbox Detection**: Precise collision detection for different attack types
- **Visual Feedback**: Hit animations and health bar updates
- **Game State Management**: Handling of active gameplay and game over states

## 🔍 Code Structure

```
stick-figure-fighting-game/
├── index.html       # Game structure and UI elements
├── style.css        # Styling for game container and UI
├── script.js        # Game logic and Fighter class implementation
└── README.md        # Project documentation
```

## 🧠 Technical Implementation

### Fighter Class

The Fighter class manages:
- Character movement and facing direction
- Jump physics with gravity
- Attack animations and hitboxes
- Health management and damage taking
- Visual hit feedback and knockback effects

### Drawing System

The game uses Canvas to draw:
- Stick figure characters with dynamic limb positions
- Ground and background elements
- Attack animations based on player actions

### Game Loop

The main game loop handles:
- Input processing from both players
- Physics updates and collision detection
- Visual rendering of all game elements
- Win/loss condition checking

## 🔄 Future Improvements

- Add special moves with button combinations
- Implement character selection with unique abilities
- Add sound effects and background music
- Create AI opponent for single-player mode
- Add mobile-friendly touch controls
- Implement online multiplayer functionality

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

Feel free to star this repo if you find it useful! Pull requests are welcome.