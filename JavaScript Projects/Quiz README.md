# Interactive Quiz App

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A dynamic and interactive quiz application built with vanilla JavaScript that offers multiple categories and customizable question counts. The app features a clean and responsive UI with animations, timer functionality, and instant feedback on answers.

![image](https://github.com/user-attachments/assets/9dbf23e3-e975-41c2-886c-572d9c79800b)
![image](https://github.com/user-attachments/assets/18bf1024-198c-4176-ad1c-083231ad94ff)
![image](https://github.com/user-attachments/assets/09dd5937-ed0d-4e70-a161-aed67c84b62a)



## Features

- **Multiple Quiz Categories:**
  - Programming
  - Geography 
  - Mathematics
  - Entertainment

- **Customizable Experience:**
  - Select your question count (5, 10, 15, 20, or 25 questions)
  - Questions randomly selected from a larger question bank for replayability
  - Category-specific content

- **Interactive UI:**
  - Animated transitions between screens and questions
  - Visual feedback for correct and incorrect answers
  - Timer countdown for each question (15 seconds)
  - Warning indicator when time is running low
  - Progress tracking through the quiz

- **Scoring System:**
  - Automatic score calculation
  - Personalized feedback based on performance
  - Option to retry with different settings

## How It Works

1. **Configuration:** Select your preferred category and number of questions
2. **Quiz:** Answer each question within the time limit
3. **Feedback:** Get immediate visual feedback on your answers
4. **Results:** View your final score and performance feedback

## Technical Implementation

The application is built using:
- HTML5 for structure
- CSS3 for styling and animations
- Vanilla JavaScript for functionality
- Bootstrap for responsive design elements
- Google Material Icons for enhanced UI elements

### Code Structure

- **Quiz Configuration:** Handles setup of quiz parameters
- **Question Management:** Randomizes and delivers questions from the selected category
- **Timer System:** Provides timed constraints for each question
- **Answer Validation:** Immediately validates and provides feedback
- **Score Tracking:** Calculates and presents final results
- **UI Animations:** Enhances user experience with smooth transitions

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quiz-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd quiz-app
   ```

3. Open `index.html` in your browser to start using the app.

No server or build process required - this app runs entirely in the browser!

## Question Bank

The application includes a comprehensive question bank with:
- 12+ Programming questions covering JavaScript, HTML, CSS, and general concepts
- 10+ Geography questions about countries, landmarks, and global features
- 10+ Mathematics questions covering various mathematical concepts
- 10+ Entertainment questions about movies, music, TV shows, and more

## Future Enhancements

- [ ] Add more quiz categories (Science, History, Sports, etc.)
- [ ] Implement difficulty levels (Easy, Medium, Hard)
- [ ] Create a leaderboard using local storage
- [ ] Add sound effects for correct/incorrect answers
- [ ] Support for user-generated question sets
- [ ] Dark mode toggle
- [ ] Accessibility improvements

## Credits

- Bootstrap for responsive UI components
- Google Material Icons for UI elements
- Customized animations for transitions

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.