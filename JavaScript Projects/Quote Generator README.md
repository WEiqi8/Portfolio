# Quote Generator

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A sleek and elegant random quote generator that displays inspirational quotes with the click of a button. Built with HTML, CSS, and vanilla JavaScript, this application provides a simple way to discover and share motivational quotes.

![image](https://github.com/user-attachments/assets/b6da2231-d273-49d3-8297-ec67cdb39938)


## Features

- **Random Quote Generation:** Instantly display a new inspirational quote with each click
- **Author Attribution:** Each quote is displayed with its respective author
- **Text-to-Speech:** Listen to quotes being read aloud using the built-in speech synthesis
- **Copy to Clipboard:** Easily copy quotes to share on social media or in messages
- **Responsive Design:** Works seamlessly across desktop and mobile devices
- **Visual Feedback:** Loading animation when generating new quotes
- **Elegant UI:** Clean and modern user interface with quote formatting

## How It Works

The application cycles through a curated collection of inspirational quotes from notable figures across history, literature, business, and more. With a simple click of the "New Quote" button, users can:

1. Generate a different random quote
2. Listen to the quote using text-to-speech functionality
3. Copy the quote to their clipboard for sharing

## Technical Implementation

Built using modern web technologies:
- **HTML5:** For structure and semantic markup
- **CSS3:** For styling and animations
- **JavaScript:** For dynamic functionality
- **Web Speech API:** For text-to-speech capabilities
- **Clipboard API:** For easy quote copying
- **Bootstrap:** For responsive layout components
- **Google Material Icons:** For intuitive UI elements

### Code Structure

- **Quote Database:** Array of quote objects containing quote text and author names
- **Random Selection:** JavaScript math functions to randomly select quotes
- **Speech Synthesis:** Web Speech API implementation for text-to-speech
- **Clipboard Management:** Modern clipboard API for copy functionality
- **Visual Feedback:** CSS transitions and loading states

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quote-generator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd quote-generator
   ```

3. Open `index.html` in your browser to start using the app.

No server or build process required - this app runs entirely in the browser!

## Quote Collection

The application includes an initial collection of inspiring quotes from notable figures including:
- Steve Jobs
- John Lennon
- Stephen King
- Martin Luther King Jr.
- Ralph Waldo Emerson
- Mary Kay Ash

## Future Enhancements

- [ ] Expand the quote collection with more inspirational quotes
- [ ] Add categories for quotes (motivation, success, happiness, etc.)
- [ ] Implement social media sharing buttons
- [ ] Allow users to submit their favorite quotes
- [ ] Add option to change background colors/themes
- [ ] Create daily quote notifications
- [ ] Add favorite/bookmark functionality for quotes

## Credits

- Bootstrap for responsive UI components
- Google Material Icons for UI elements
- Web Speech API for text-to-speech functionality

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.