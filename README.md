# Typing Speed Game

A Java-based typing game that tests and improves your typing speed and accuracy through multiple difficulty levels.

![Game Screenshot](screenshot.png) *(Consider adding a screenshot later)*

## Features

- 🕒 90-second timed gameplay
- 📈 8 progressive difficulty levels
- 🎯 Score tracking and streak bonuses
- ⏱️ Time penalties for incorrect answers
- 🔄 Restart functionality
- 🎮 Simple and intuitive UI

## How to Play

1. Click the **Start** button to begin the game
2. Type the word displayed in the main label and press Enter
3. The next word will appear - keep typing as many as you can!
4. Earn +5 seconds for every 5 correct answers in a row
5. Lose -5 seconds for each incorrect answer
6. Game ends when time runs out

## Game Mechanics

- Words are loaded from 8 different difficulty level files
- Progressively moves to harder levels as you play
- Current score and remaining time are displayed
- See the next upcoming word to prepare

## Requirements

- Java 8 or higher
- Text files containing words for each level in `/Words/` directory
- Icon files in `/Icons/` directory (optional)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/typing-game.git
2. Compile the Java files:

  ```bash
  javac Typer.java

3. Run the application:

```bash
java Typer
