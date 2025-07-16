# Rock Paper Scissors Game

A simple web-based Rock Paper Scissors game built with HTML, CSS, and JavaScript.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [License](#license)

## Overview

This project lets users play Rock Paper Scissors against the computer. The game keeps track of wins, losses, and ties using the browser's localStorage, so your score persists even after refreshing the page.

## Features

- Play Rock, Paper, or Scissors against the computer.
- Score tracking (wins, losses, ties) saved in localStorage.
- Visual feedback for each round.
- Reset score functionality.
- Responsive design for desktop and mobile.

## How to Play

1. Open `10-rock-paper-scissors .html` in your browser.
2. Click on your move (Rock, Paper, or Scissors).
3. The computer randomly selects its move.
4. The result and updated score are displayed.
5. Use the reset button to clear your score.

## Project Structure

```
projects.upload/
├── 10-rock-paper-scissors .html   # Main HTML file
├── 10-rock-paper-scissors.js      # JavaScript logic
├── 10-rock-paper-scissors.css     # Stylesheet
├── images/                        # Emoji images for moves
└── README.md                      # Project documentation
```

## How It Works

- **Game Logic:**  
  The JavaScript (`10-rock-paper-scissors.js`) handles user input, randomly picks the computer's move, determines the result, updates the score, and saves it in localStorage.
- **UI:**  
  The HTML and CSS files provide a simple interface with buttons for each move and display the results and score.
- **Persistence:**  
  Scores are stored in localStorage so they remain after page reloads.

## Screenshots

![Game Screenshot](images/rock-emoji.png)

## Credits

- Emojis from [OpenMoji](https://openmoji.org/) or system emoji set.

## License

This project is for educational purposes