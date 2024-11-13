# Guess-the-number

A simple number guessing game built in Python where the computer randomly selects a number between 1 and 100, and the user has to guess the number. The game provides feedback after each guess and tracks the number of attempts. If a new high score is achieved, it updates the record.

## Features
- Random number generation between 1 and 100.
- Feedback on each guess, indicating if the guess is too high or too low.
- High score tracking, which saves the best attempt count in a file (`hiscore.txt`).

## How to Run the Game
1. Make sure you have Python installed on your machine.
2. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/NumberGuessingGame.git
    ```
3. Navigate into the directory:
    ```bash
    cd NumberGuessingGame
    ```
4. Run the Python script:
    ```bash
    python main.py
    ```

## How the High Score Works
- The game reads from `hiscore.txt` to check the current high score.
- If the player beats the high score, the game will update `hiscore.txt` with the new score.

## Files
- `main.py`: The main Python script that contains the game logic.
- `hiscore.txt`: A text file that stores the minimum number of guesses taken to guess the number correctly.

## Sample Output
