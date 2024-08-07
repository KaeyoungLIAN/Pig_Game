# Pig Game
## Project Overview
This project is an implementation of the Pig game using JavaScript. In this game, players take turns rolling a dice, accumulating points until they either choose to hold their score or roll a 1, which ends their turn and switches the active player. The first player to reach or exceed 100 points wins the game. The project involves selecting DOM elements, handling button clicks for rolling the dice, holding the score, and starting a new game, as well as updating the UI dynamically based on the game state.

## Features
- Turn-Based Gameplay: Players take turns to roll the dice and accumulate points.
- Dice Rolling: A random number between 1 and 6 is generated for each roll.
- Score Holding: Players can hold their current score to avoid the risk of rolling a 1.
- Switch Player: The game automatically switches the active player when a 1 is rolled or when the player holds their score.
- Winning Condition: The first player to reach or exceed 100 points wins the game.

## Technologies Used
- HTML: For structuring the game interface.
- CSS: For styling the game elements.
- JavaScript: For game logic and interactivity.

## How to Play
Open the game in a web browser.
Player 1 starts the game by clicking the "Roll Dice" button.
If the dice roll is not a 1, the rolled number is added to the current score. If the dice roll is a 1, the turn switches to Player 2.
Players can choose to hold their current score by clicking the "Hold" button. This adds the current score to their total score and switches the turn to the other player.
The first player to reach or exceed 100 points wins the game.
Click the "New Game" button to reset the game and start a new round.
