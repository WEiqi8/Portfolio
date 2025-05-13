# Typing Speed Challenge

A web-based application to test and improve your typing speed and accuracy with a timed challenge.

![image](https://github.com/user-attachments/assets/45f958c8-011d-452b-8be7-06866a5da6a6)
![image](https://github.com/user-attachments/assets/3048e38f-ab1f-4c97-bf90-50124df80534)
![image](https://github.com/user-attachments/assets/dc89ca01-cbfc-4f25-8fa8-d56cffaccc2a)


## Features

- 60-second typing speed test
- Real-time feedback with character-by-character highlighting
- Performance metrics including:
  - Words Per Minute (WPM)
  - Characters Per Minute (CPM)
  - Mistake counter
  - Countdown timer
- Random selection from motivational and business-focused paragraphs
- Prevents cheating (copy-paste is disabled)
- Responsive design for various screen sizes
- Interactive UI with start and end modals

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- DOM Manipulation
- Event Handling

## Live Demo

[View Live Demo](https://yourusername.github.io/typing-speed-challenge)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/typing-speed-challenge.git
   ```

2. Navigate to the project directory:
   ```
   cd typing-speed-challenge
   ```

3. Open `index.html` in your preferred browser.

## How to Use

1. When the page loads, you'll see a random paragraph and a start prompt
2. Click the "Start Typing" button to begin the 60-second challenge
3. Type the displayed text as quickly and accurately as possible
4. Correct characters will highlight in green, incorrect ones in red
5. Your performance metrics update in real-time:
   - Time remaining (counts down from 60 seconds)
   - Number of mistakes made
   - Words Per Minute (WPM)
   - Characters Per Minute (CPM)
6. The game ends when either:
   - The 60-second timer expires
   - You complete typing the entire paragraph
7. View your final results in the Game Over modal
8. Click "Close" to restart with a new paragraph

## Project Structure

```
typing-speed-challenge/
│
├── index.html          # The main HTML structure
├── style.css           # CSS styles (not included in the repository)
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Technical Implementation

- **Dynamic Text Rendering**: Converts paragraphs into individual character spans for highlighting
- **Hidden Input Field**: Creates an invisible input that captures keystrokes while maintaining visual design
- **Real-time Metrics Calculation**:
  - WPM calculated as (correct characters / 5) / time elapsed
  - CPM calculated as correct characters / time elapsed
- **Character-by-Character Validation**: Compares each typed character against the reference text
- **Event-Driven Architecture**: Uses event listeners for user interactions
- **Focus Management**: Ensures typing input remains focused during the game

## Future Enhancements

- User accounts to save progress and high scores
- Difficulty levels with different text complexities
- Custom time settings (30s, 60s, 120s challenges)
- Multiplayer mode to compete with friends
- Additional statistics like accuracy percentage
- Custom text input option
- Mobile-optimized version with virtual keyboard support

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.



