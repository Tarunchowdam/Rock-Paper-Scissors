# Rock Paper Scissors Game

## Overview

This is a simple implementation of the classic Rock Paper Scissors game using HTML and JavaScript. Players can choose their move (rock, paper, or scissors) by clicking on the respective buttons, and the computer generates its move randomly. The game logic determines the winner, and the scores are tracked and displayed.

## How to Play

1. Open the `index.html` file in a web browser.
2. Click on the buttons to choose your move: Rock, Paper, or Scissors.
3. The computer will randomly select its move.
4. The game will display the result, and the scores will be updated accordingly.
5. You can reset the score by clicking the "Reset Score" button.

## Files

- `index.html`: The main HTML file containing the structure of the game.
- `style.css`: The CSS file for styling the game elements.
- `rock-emoji.png`, `paper-emoji.png`, `scissors-emoji.png`: Emoji images for each move.
- `README.md`: This file providing an overview and instructions.

## Score Tracking

The game keeps track of wins, losses, and ties. The scores are stored in the browser's local storage, allowing for persistence even when the page is refreshed.

## Resetting the Score

To reset the score to zero wins, zero losses, and zero ties, click the "Reset Score" button.

## Developer Notes

- The game logic is implemented in the `playGame` function.
- The computer's move is randomly generated using the `pickComputerMove` function.
- Scores are stored and retrieved from local storage using JavaScript.
