# GeminiChat - A Modern AI Chatbot with Google's Gemini API

## Project Overview

GeminiChat is a responsive web-based AI chatbot that leverages Google's Gemini 2.0 Flash API. This interactive application allows users to have natural conversations with an AI assistant, upload files (including images) for context, and enjoy a clean, user-friendly interface with both light and dark themes.

## Features

- **Real-time AI Conversations**: Engage in dynamic conversations with Google's powerful Gemini 2.0 Flash language model
- **Realistic Typing Effect**: AI responses are displayed with a natural typing animation
- **File Upload Support**: Attach images and documents (PDF, TXT, CSV) to provide additional context to your queries
- **Theme Toggle**: Switch between dark and light modes with preferences saved in local storage
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Conversation Management**: Clear chat history and stop ongoing responses
- **Quick Suggestions**: Pre-populated suggestions for common queries

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5
- **API**: Google's Gemini 2.0 Flash API
- **Icons**: Google Material Symbols
- **Storage**: LocalStorage for user preferences

## Implementation Details

The application is built with a clean separation of concerns and modern JavaScript practices:

- **Dynamic DOM Manipulation**: Creates chat elements on-the-fly for a seamless experience
- **Asynchronous API Calls**: Uses Fetch API with AbortController for manageable requests
- **Base64 File Encoding**: Converts uploaded files to base64 for API transmission
- **Event Delegation**: Efficiently handles user interactions across the interface
- **Chat History Management**: Maintains conversation context for more coherent AI responses

## Getting Started

1. Clone the repository
2. Replace the `API_KEY` in script.js with your Google Gemini API key
3. Open index.html in your browser or deploy to your preferred hosting service

## Future Enhancements

- Voice input and output capabilities
- Support for additional file formats
- Message saving and exporting
- Custom styling options
- User authentication for personalized experiences
- Chat History

## Screenshots
-Light Theme
![image](https://github.com/user-attachments/assets/c4764a6d-9492-4856-bc59-1cd0826d75a5)

-Dark Theme (same features)
![image](https://github.com/user-attachments/assets/5f35ec85-bd55-4f89-9085-7fd488514b8d)

---

Feel free to use this project as a starting point for your own AI chatbot applications or contribute to its development!
