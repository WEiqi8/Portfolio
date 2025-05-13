# Classic Pong Game

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A modern recreation of the classic arcade game Pong with both single player and multiplayer options. Built with HTML5 Canvas and vanilla JavaScript.

![image](https://github.com/user-attachments/assets/a50acf62-620c-4dc8-80af-54c7c26e0203)

## Features

- **Two Game Modes:**
  - Single Player (compete against AI)
  - Multiplayer (local 2-player gameplay)
- **Progressive Difficulty:**
  - Increasing ball speed and paddle speed as you advance through rounds
  - Color changes between rounds for visual distinction
- **UI Controls:**
  - Play/Resume button
  - Pause button
  - Restart game option
  - Mode selection interface
- **Scoring System:**
  - Round-based gameplay with target scores
  - Multiple levels with increasing difficulty
- **Responsive Design:**
  - Canvas scaling for different screen sizes

## How to Play

### Controls
- **Single Player Mode:**
  - Use W/S keys or Up/Down arrow keys to control the left paddle
  - AI controls the right paddle
  
- **Multiplayer Mode:**
  - Player 1: W (up) and S (down) keys for the left paddle
  - Player 2: Up ↑ and Down ↓ arrow keys for the right paddle

### Game Rules
- Score points by making the ball pass your opponent's paddle
- First to reach the target score for the current round wins
- The game consists of multiple rounds with increasing difficulty
- Complete all rounds to win the game

## Technical Implementation

The game is built using:
- HTML5 Canvas for rendering
- Vanilla JavaScript for game logic
- Object-oriented programming approach
- Collision detection algorithms
- AI opponent with adaptive difficulty

### Code Structure

- **Game Objects:**
  - Ball: Controls the bouncing ball mechanics
  - Paddle: Manages player and AI paddle movement
  - Game: Main game loop and state management

- **Key Features Implemented:**
  - Collision detection for paddles and walls
  - Score tracking and round progression
  - AI opponent with difficulty scaling
  - Game state management (paused, running, over)
  - Input handling for keyboard controls

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pong-game.git
   ```

2. Navigate to the project directory:
   ```bash
   cd pong-game
   ```

3. Open `index.html` in your web browser to play.

No additional dependencies or build steps are required.

## Future Improvements

- [ ] Add sound effects for ball hits, scoring, and game events
- [ ] Implement mobile touch controls for tablet/phone play
- [ ] Add power-ups that appear during gameplay
- [ ] Create online multiplayer using WebSockets
- [ ] Add customization options for paddle and ball appearance
- [ ] Implement different AI difficulty levels

## Credits

- Original Pong game concept by Atari (1972)
- Modern implementation by Wei Qi
- Inspired by classic arcade games

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.