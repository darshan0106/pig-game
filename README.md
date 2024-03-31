# Pig Game

Welcome to the Pig Game repository! This project contains a JavaScript implementation of the Pig Game, a simple dice game where players take turns rolling a dice and accumulating points. The goal is to reach a specified score (usually 100) before your opponent.

## About the Game

In the Pig Game, two players compete against each other. On each turn, a player rolls a dice multiple times, accumulating points with each roll. However, if the player rolls a 1, their current score is reset to zero, and it becomes the next player's turn. The player can choose to "hold" their current score, adding it to their total score and ending their turn. The first player to reach the winning score wins the game.

## About the Code

The JavaScript code implements the functionality of the Pig Game, including rolling the dice, updating scores, switching players, and determining the winner. Let's explore the key components of the code:

- **Initialization**: The `init` function initializes the game by setting initial scores, current score, active player, and game state. It also resets the UI elements to their default state.

- **Switching Players**: The `switchPlayer` function switches the active player and resets the current score to zero. It also updates the UI to reflect the active player.

- **Rolling the Dice**: When the "Roll Dice" button is clicked, a random dice roll is generated, and the corresponding dice image is displayed. If the rolled number is 1, the current score is reset, and the turn switches to the next player.

- **Holding Score**: When the "Hold" button is clicked, the current score is added to the active player's total score. If a player reaches the winning score, the game ends, and that player is declared the winner.

## How to Play

1. Open the Pig Game in your web browser.
2. Click the "Roll Dice" button to roll the dice.
3. Accumulate points with each roll, but be careful not to roll a 1!
4. Click the "Hold" button to add your current points to your total score and switch to the next player.
5. The first player to reach the winning score wins the game!

## Customization

You can customize the Pig Game in various ways, including:

- **Changing Winning Score**: Modify the `winningScore` variable to set a different winning score for the game.
- **Adding Features**: Extend the game with additional features such as player customization, animations, or sound effects.
- **Styling**: Customize the CSS styles to change the appearance and layout of the game elements.

## Contributing

Contributions to the Pig Game project are welcome! If you have ideas for improvements, new features, or bug fixes, please feel free to contribute by submitting a pull request or opening an issue on the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE), allowing for open collaboration and adaptation.
