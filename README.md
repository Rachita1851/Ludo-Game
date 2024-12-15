# Ludo Game in Python

This is a simple text-based implementation of the classic board game **Ludo**. Players take turns to roll a dice, and the first player to reach position 50 wins the game.

## Features
- Two players: Player 1 and Player 2.
- Players take turns rolling a dice.
- Movement updates are displayed after each turn.
- Automatic winner detection when a player reaches the winning position.

## How to Run
1. Clone this repository or download the script file.
2. Ensure Python is installed on your system.
3. Open a terminal or command prompt and navigate to the directory containing the script.
4. Run the script using the command:
   ```
   python ludo_game.py
   ```
5. Follow the prompts to play the game.

## Gameplay Instructions
1. The game alternates turns between Player 1 and Player 2.
2. On your turn, press `Enter` to roll the dice.
3. The dice roll value determines how far your player moves.
4. The first player to reach position 50 is declared the winner.

## Example Gameplay
```
Welcome to the Ludo Game!
First player to reach position 50 wins!
------------------------------

Player 1's turn:
Player 1 rolled a 4
Player 1 moves to position 4

Player 2's turn:
Player 2 rolled a 6
Player 2 moves to position 6
...
Congratulations! Player 1 has won the game by reaching position 50!
```

## Customization
- Modify the `WINNING_POSITION` variable to change the target position for winning.
- Adjust the `roll_dice` function to implement custom dice logic.

## Requirements
- Python 3.x

