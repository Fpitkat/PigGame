# Dice Game

This project is a simple, interactive dice game implemented in JavaScript. The game is designed for two players who take turns rolling a dice. The game is played in a browser and uses HTML and CSS for the user interface.

## How the Game Works

1. Players take turns to roll a dice. The result of the dice roll is added to the player's current score.
2. If a player rolls a 1, their turn is over and their current score is reset to 0.
3. A player can choose to 'hold', which means their current score is added to their total score. After a player holds, it's the other player's turn.
4. The first player to reach or exceed 100 points on their total score wins the game.

## Code Overview

The JavaScript code controls the game logic. Here's a brief overview of what some of the code does:

- The `btnRoll` event listener handles the dice roll. It generates a random number between 1 and 6, displays the corresponding dice image, and updates the current score or switches the player if a 1 is rolled.
- The `btnHold` event listener handles the hold action. It adds the current score to the active player's total score and checks if the player has won the game.
- The `switchPlayer` function switches the active player and resets the current score.
- The `player--winner` class is added to the winning player, and the `player--active` class is removed.

## How to Run the Project

To run this project, simply open the HTML file in your web browser. No additional installation is required.
