# Pig_Game
This project is an implementation of the Pig game using JavaScript. In this game, players take turns rolling a dice, accumulating points until they either choose to hold their score or roll a 1, which ends their turn and switches the active player. The first player to reach or exceed 100 points wins the game. The project involves selecting DOM elements, handling button clicks for rolling the dice, holding the score, and starting a new game, as well as updating the UI dynamically based on the game state.

Here’s a brief breakdown of the project:
## Selecting Elements:
The script selects various HTML elements, including player panels, score displays, current score displays, the dice image, and control buttons (New Game, Roll Dice, Hold).
## Starting Conditions: 
Initial scores are set to 0, and the dice is hidden.
## Game State Variables: 
Variables are defined to keep track of scores, current score, active player, and game state (playing or not).
## Switch Player Function:
A function to handle the switching of the active player, resetting the current score, and toggling the active player’s UI class.
## Rolling Dice Functionality: 
Adds an event listener to the Roll Dice button. When clicked, it generates a random dice roll, updates the UI, and checks if the roll is 1. If so, it switches the player; otherwise, it adds to the current score.
## Hold Button Functionality: 
Adds an event listener to the Hold button. When clicked, it adds the current score to the active player's total score, checks if the player has won, and updates the UI accordingly. If no one has won, it switches the player.
## New Game Button Functionality: 
Adds an event listener to the New Game button. When clicked, it resets all scores, the game state, and the UI to start a new game.
