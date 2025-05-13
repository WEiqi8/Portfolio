# WordGuess - Interactive Hangman Game

## Project Overview

WordGuess is an engaging, interactive Hangman game that challenges players to guess words letter by letter before the hangman is complete. This modern implementation features a clean interface, keyboard interaction, visual feedback, and a diverse collection of words with helpful hints across various categories including science, nature, everyday objects, and mythology.

![image](https://github.com/user-attachments/assets/bfd5fc40-8f52-4a1b-ac7f-e5f6bfdc4998)
![image](https://github.com/user-attachments/assets/345e2918-648d-4c6f-bc4f-c32950c10d61)
![image](https://github.com/user-attachments/assets/cc5390e7-20ea-4a26-a864-1642ab378006)

## Features

- **Extensive Word Bank**: 30+ carefully selected words with corresponding hints
- **Interactive Keyboard**: On-screen clickable keyboard with visual feedback
- **Physical Keyboard Support**: Play using your computer keyboard for a seamless experience
- **Progressive Difficulty**: Words range from simple to challenging
- **Visual Feedback System**: 
  - Hangman image progressively appears with each incorrect guess
  - Crossed-out letters for incorrect guesses
  - Revealed letters for correct guesses
- **Game State Tracking**:
  - Incorrect letter display
  - Remaining guesses counter
  - Game over detection with word reveal
- **Responsive Design**: Optimized for both desktop and mobile play

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5
- **jQuery**: Light usage for selector enhancements
- **Custom Fonts**: Google Fonts (Atma) for a playful appearance
- **DOM Manipulation**: Dynamic content generation and updates
- **Event Handling**: Keyboard and mouse input processing

## Implementation Details

The application leverages several technical features:

- **Set Collections**: Using JavaScript Sets for efficient letter tracking
- **Event Delegation**: Handling keyboard and mouse interactions
- **Custom CSS Styles**: Dynamic style injection for visual feedback
- **Random Word Selection**: Algorithm for selecting words from the word bank
- **Game State Management**: Tracking guesses and game progression
- **Custom jQuery Selector**: Implementation of the `:contains` selector for enhanced DOM querying
- **Modal System**: Game over notification with play again functionality

## How to Play

1. The game starts with a randomly selected word represented by blank spaces
2. A hint about the word is provided
3. Guess letters by clicking the on-screen keyboard or using your physical keyboard
4. Correct guesses reveal the letter in its position in the word
5. Incorrect guesses add to the hangman image and are crossed out
6. Win by guessing all letters before the hangman is complete (6 incorrect guesses)
7. If you lose, the correct word is revealed and you can play again

## Getting Started

1. Clone the repository
2. Ensure you have the hangman image files (numbered 1-7) in the project directory
3. Open index.html in your browser or deploy to your preferred hosting service

## Customization Options

The game can be easily customized by:
- Adding new words and hints to the `words` array
- Adjusting the maximum number of guesses allowed
- Changing the hangman images
- Modifying the CSS styles for a different visual theme

## Future Enhancements

- Word categories for themed gameplay
- Difficulty levels with adjustable time limits
- Scoring system and leaderboard
- Hint reveal option with score penalty
- Sound effects and animations
- Two-player mode where one player sets the word


## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

A perfect blend of classic gameplay and modern web technologies, WordGuess offers an entertaining challenge for players of all ages.