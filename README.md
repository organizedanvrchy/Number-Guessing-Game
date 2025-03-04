# Number Guessing Game

## Summary
This Python script is a simple number guessing game where the player must guess a randomly generated number between 1 and 100. The player can choose between two difficulty levels: "Easy" (10 attempts) or "Hard" (5 attempts). The game provides feedback on each guess, indicating whether the guess is too high, too low, or close to the target number. The game ends when the player either guesses the correct number or runs out of attempts. The program also allows the player to replay the game after each round.

## Features
- **Random Number Generation**: The program uses the `random` module to generate a random number between 1 and 100.
- **Difficulty Levels**: The player can choose between two difficulty levels:
  - **Easy**: 10 attempts to guess the number.
  - **Hard**: 5 attempts to guess the number.
- **Input Validation**: The program ensures that the player's input is a valid number and handles invalid inputs gracefully.
- **Feedback System**: The game provides feedback on each guess, indicating whether the guess is too high, too low, or close to the target number.
- **Attempt Tracking**: The number of remaining attempts is displayed after each guess.
- **Replayability**: The player can choose to play again after each round, allowing for multiple games in a single session.
- **Win/Lose Conditions**: The game ends when the player either guesses the correct number (win) or runs out of attempts (lose). The correct number is displayed at the end of the game.

## How to Play
1. Run the script in a Python environment.
2. Choose a difficulty level by typing `Easy` or `Hard`.
3. Guess the number by entering a number between 1 and 100.
4. The game will provide feedback on your guess, indicating whether it is too high, too low, or close to the target number.
5. Continue guessing until you either guess the correct number or run out of attempts.
6. After each round, you can choose to play again or exit the game.

## Requirements
- Python 3.x

## Running the Game
To run the game, simply execute the script in your Python environment:
```bash
python main.py
