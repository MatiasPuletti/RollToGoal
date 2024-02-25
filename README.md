# 🎲 Roll To Goal!

## Overview
This Dice Game is a simple, interactive browser-based game built using JavaScript. The game involves two players who take turns rolling a dice to accumulate points. The goal is to be the first player to reach or exceed 100 points. Players can roll the dice as many times as they wish per turn but risk losing all points accumulated in that turn if they roll a 1. They can choose to "hold" their points at any time, which adds their current turn points to their total and passes the turn to the other player.

## Features

- **Dice Roll**: Players can roll the dice to get a random number between 1 and 6. The result is displayed on the screen with a dice image.
- **Accumulate Points**: Points from each dice roll are added to the player's current score until they either choose to hold or roll a 1.
- **Switch Turns**: When a player rolls a 1 or chooses to hold, the turn switches to the other player.
- **Hold Functionality**: Players can choose to hold their current points, which are then added to their total score. The turn is then passed to the other player.
- **Winning Condition**: The game ends when a player reaches or exceeds 100 points, and they are declared the winner.
- **New Game**: At any time, players can start a new game, resetting all scores and the winner status.

## Concepts Learned

1. **DOM Manipulation**: The game demonstrates the use of the Document Object Model (DOM) to interact with and modify HTML elements, including selecting elements, changing text content, and toggling classes.
2. **Event Handling**: It showcases how to respond to user actions, such as button clicks, using event listeners to trigger game functionality.
3. **Control Structures**: The game logic incorporates if-else statements and ternary operators for decision-making, such as checking the dice roll outcome and determining the game state.
4. **Function Definitions and Calls**: Functions are defined for initializing the game, switching players, and handling dice rolls and hold actions, illustrating the concept of code reuse and modularity.
5. **Variable Scope and Management**: The use of global and local variables is evident, managing game state such as scores, current score, active player, and game playing status.
6. **Conditional Rendering**: The game dynamically shows or hides elements, like the dice image, and applies CSS classes based on the game state, demonstrating conditional rendering in web applications.

## The Game!
   
<img width="1074" alt="Screenshot 2024-02-25 at 17 39 13" src="https://github.com/MatiasPuletti/RollToGoal/assets/68690366/19418124-3467-457d-b4a8-c2a130fbe071">

## Getting Started

To play the game, simply open the HTML file in a web browser. The game interface will allow you to roll the dice, hold your score, and see each player's total and current scores. Enjoy the game and may the best player win!

