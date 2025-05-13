# 🐍 My Python Coding Journey

This repository documents my programming journey through Python, showcasing various projects ranging from machine learning applications to practical tools and games. Each project demonstrates different aspects of Python programming, from data analysis to interactive applications.

## 📚 Table of Contents

1. [Machine Learning Projects](#machine-learning-projects)
2. [Personal Assistant Telegram Bot](#personal-assistant-telegram-bot)
3. [Terminal Expense Tracker](#terminal-expense-tracker)
4. [Python Checkers Game](#python-checkers-game)
5. [Setup Instructions](#setup-instructions)

---

## Machine Learning Projects

A collection of machine learning projects developed using Python and Jupyter Notebook. Each notebook explores a different domain, using data science and machine learning techniques to solve real-world problems.

### 🚗 Car Price Predictions

**File:** `Car price predictions.ipynb`

#### 📌 Objective
Predict the price of a car based on features like year, brand, mileage, and fuel type using regression models.

#### 🔧 Tools Used
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn (Linear Regression, Random Forest, etc.)

#### 🧱 Key Steps
- Data preprocessing and visualization  
- Feature engineering  
- Regression model training and evaluation

#### Best Model: XGBoost Regressor
- Train R² Score: 0.8503
- Test R² Score: 0.5486
- Achieved the best performance among tested models
- Used feature engineering and data preprocessing for improved performance
- Visualized feature importance to interpret which factors most influence price predictions

### 🧬 Personality Prediction

**File:** `Personality Prediction.ipynb`

#### 📌 Objective
Predict a person's MBTI (Myers–Briggs Type Indicator) personality type based on their writing/text data.

#### 🔧 Tools Used
- Natural Language Processing (NLP)  
- TF-IDF, CountVectorizer  
- Logistic Regression, SVM, Naive Bayes

#### 🧱 Key Steps
- Text preprocessing and vectorization  
- Multi-class classification modeling  
- Evaluation using accuracy and confusion matrix

### 📰 Fake News Detection

**File:** `Fake news detection.ipynb`

#### 📌 Objective
Classify whether a news article is fake or real using its title and content.

#### 🔧 Tools Used
- NLP tools and techniques  
- TF-IDF for feature extraction  
- Machine learning models like Logistic Regression, Passive Aggressive Classifier

#### 🧱 Key Steps
- Cleaning and tokenizing text  
- Feature extraction with TF-IDF  
- Binary classification and evaluation

#### Model Used: Decision Tree Classifier
- Accuracy Score: 99.54%
- Applied text preprocessing techniques
- Converted text into numerical form using TF-IDF Vectorization
- Demonstrates excellent precision and recall

### 💬 Sentiment Analysis

**File:** `Sentiment Analysis.ipynb`

#### 📌 Objective
Analyze the sentiment of text data (e.g., tweets, reviews) and classify it as positive, negative, or neutral.

#### 🔧 Tools Used
- Pandas, Scikit-learn, NLTK  
- Logistic Regression / Naive Bayes  
- TF-IDF Vectorization

#### 🧱 Key Steps
- Text cleaning and preprocessing  
- Feature extraction with TF-IDF  
- Model training and sentiment prediction

### 🔍 Recommendation System

**File:** `Recommendations.ipynb`

#### 📌 Objective
Recommend items such as movies, books, or products based on user preferences using both content-based and collaborative filtering techniques.

#### 🔧 Tools Used
- Pandas, Scikit-learn  
- Cosine similarity  
- Surprise (optional for collaborative filtering)

#### 🧱 Key Steps
- Data analysis and preprocessing  
- Implementing content-based filtering  
- Implementing collaborative filtering

---

## Personal Assistant Telegram Bot

A versatile Personal Assistant Telegram Bot that helps you manage contacts, set reminders, and provides a friendly chat experience.

**Try it now:** @Helper111666_bot

### ✨ Features

#### 📱 Contact Management
* Save and organize your contacts
* Send messages to saved contacts (simulation)
* View your contact list

#### ⏰ Reminder System
* Set daily reminders with custom messages
* Receive notifications at specified times
* Manage and delete your reminders

#### 💬 Chat Functionality
* Engage in casual conversation with the bot
* Get jokes, respond to greetings, and more
* Natural language interaction

### 🚀 Getting Started
1. **Find the bot on Telegram:**
   * Search for @Helper111666_bot in Telegram
   * Or click the link: https://t.me/Helper111666_bot
2. **Start a conversation:**
   * Send `/start` to begin
   * The bot will present you with available options

### 📋 Available Commands
| Command | Description |
|---------|-------------|
| `/start` | Start interacting with the bot |
| `/help` | View all available commands and features |
| `/send` | Send a message to a contact |
| `/addcontact` | Add a new contact to your list |
| `/contacts` | View all your saved contacts |
| `/reminder` | Set a new daily reminder |
| `/reminders` | View and manage your reminders |
| `/chat` | Start a friendly conversation with the bot |
| `/cancel` | Cancel the current operation |

### 🔒 Privacy
This bot stores:
* Your contacts (name and phone number)
* Your reminders (time and message content)
* Limited chat history for better conversation flow

All data is stored locally and used only to provide functionality. Message sending is simulated and doesn't actually send SMS messages to the specified contacts.

### 🛠️ Technical Details
Built with:
* Python 3.8+
* python-telegram-bot library
* schedule library for reminder management
* JSON file storage for user data

---

## Terminal Expense Tracker

A beautiful terminal-based expense tracking application with rich visual formatting and graphical visualization capabilities.

### Overview
Terminal Expense Tracker is a Python command-line application that helps you keep track of your expenses with a clean, colorful interface. The application uses the rich library for beautiful terminal formatting and matplotlib for expense visualization.

### Features
- **User-Friendly Interface**: Colorful and intuitive terminal UI using rich
- **Complete Expense Management**:
  - Add new expenses with names and amounts
  - View all expenses in a formatted table
  - Edit existing expenses
  - Delete unwanted expenses
- **Data Visualization**: Display expenses in a graphical bar chart
- **Interactive Prompts**: Enhanced user experience with interactive prompts and confirmations

### Requirements
- Python 3.6+
- Required packages:
  - rich
  - matplotlib

### Installation
1. Ensure you have Python 3.6+ installed on your system
2. Install the required packages:
```bash
pip install rich matplotlib
```
3. Download the `expense_tracker.py` file
4. Run the application:
```bash
python expense_tracker.py
```

### Usage Guide
1. **Adding an Expense**: Select option `1` from the main menu
2. **Viewing Expenses**: Select option `2` from the main menu
3. **Editing an Expense**: Select option `3` from the main menu
4. **Deleting an Expense**: Select option `4` from the main menu
5. **Visualizing Expenses**: Select option `5` from the main menu
6. **Exiting the Application**: Select option `6` from the main menu

---

## Python Checkers Game

A feature-rich implementation of the classic Checkers (Draughts) game playable in the terminal.

### Overview
This Python-based Checkers game offers a complete implementation of the traditional board game with an intuitive command-line interface. The game supports standard checkers rules including piece capturing, king promotion, and multiple jumps.

### Features
- **Complete Rules Implementation**: Standard checkers rules including required captures and king movements
- **Multiple Input Methods**:
  - Chess-style notation (e.g., "c6 d5")
  - Numbered piece selection (e.g., "3 2" for piece #3 to its 2nd possible destination)
  - Traditional coordinates (e.g., "6 1 5 0")
- **Visual Board Display**: Clear Unicode-based board representation
- **Interactive Help**: Comprehensive in-game help and instructions
- **Move Hints**: Optional hints showing all possible moves (can be toggled on/off)
- **Game Status Tracking**: Tracks pieces, available moves, and determines game completion

### How to Play
#### Setup
1. Ensure you have Python installed on your system
2. Save the `checkers_game.py` file to your preferred location
3. Run the game using:
   ```
   python checkers_game.py
   ```

#### Game Controls
The game supports three different ways to move pieces:

1. **Chess Notation**:
   - Enter moves in the format "from to" using chess-style coordinates
   - Example: `c6 d5` (move from c6 to d5)
   - Letters (a-h) represent columns left to right
   - Numbers (1-8) represent rows bottom to top

2. **Numbered Piece Selection**:
   - Type `list` to see all your movable pieces with numbers
   - Enter moves as "piece# destination#"
   - Example: `3 2` (move piece #3 to its destination option #2)

3. **Traditional Coordinates**:
   - Enter as "row col row col" (counting from 0 at top-left)
   - Example: `6 1 5 0` (move from row 6, column 1 to row 5, column 0)

#### Additional Commands
- `list`: Display all movable pieces with numbers
- `help`: Show the in-game help menu
- `hints on`/`hints off`: Toggle move suggestions
- `q`: Quit the game

### Game Rules
- Player 1 (○) starts at the bottom of the board
- Player 2 (●) starts at the top of the board
- Pieces move diagonally forward only (kings can move in any direction)
- Captures are made by jumping over opponent pieces
- Multiple jumps in one turn are required when possible
- Pieces are promoted to kings (♔/♚) when they reach the opposite edge
- The game ends when a player cannot move or has no pieces left

---

## Setup Instructions

### General Requirements
1. Python 3.6+ installed on your system
2. Git for cloning the repository (optional)

### Clone the Repository
```bash
git clone https://github.com/yourusername/python-coding-journey.git
cd python-coding-journey
```

### Install Required Libraries
```bash
pip install -r requirements.txt
```

### Running the Projects
- **Machine Learning Projects**: Open notebooks using Jupyter
  ```bash
  jupyter notebook
  ```
- **Telegram Bot**: Set up your bot token and run
  ```bash
  python telegram_bot.py
  ```
- **Expense Tracker**: Launch the application
  ```bash
  python expense_tracker.py
  ```
- **Checkers Game**: Start the game
  ```bash
  python checkers_game.py
  ```

---

## 🌱 My Growth as a Python Developer

This repository represents my journey in Python programming, showing progression from basic concepts to more complex applications. Through these projects, I've gained experience in:

- Data analysis and machine learning
- Working with APIs and web services
- Building interactive command-line applications
- Creating practical tools for everyday use
- Game development and UI design in terminal environments

Each project reflects a different aspect of my skills and interests in Python development, from practical utilities to AI-powered applications.

---

## 📊 Skills Demonstrated

- **Data Science & ML**: Regression, classification, NLP, sentiment analysis
- **API Integration**: Telegram Bot API
- **UI Design**: Terminal-based UIs with rich formatting
- **Data Structures**: Lists, dictionaries, custom objects
- **Algorithm Implementation**: Game logic, ML models
- **Software Architecture**: Multi-component applications

---

Feel free to explore each project folder to learn more about individual implementations!