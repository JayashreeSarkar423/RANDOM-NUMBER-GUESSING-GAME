# Number Guessing Game

A simple and interactive number guessing game built using Python.

## About the Project

In this game, the computer randomly selects a number between 1 and 10. The player has to guess the correct number.

The game provides hints:

* **Higher number:** If the guessed number is smaller than the actual number.
* **Lower number:** If the guessed number is greater than the actual number.
* **Correct number guessed:** If the player guesses the correct number, the game ends.

## Features

* Random number generation
* Interactive user input
* Higher and lower hints
* Unlimited guessing attempts
* Simple and beginner-friendly Python code

## Requirements

* Python 3.x
* Any Python IDE (IDLE, VS Code, PyCharm, etc.)

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/number-guessing-game.git
   ```

2. Open the project folder:

   ```bash
   cd number-guessing-game
   ```

3. Run the Python program:

   ```bash
   python main.py
   ```

## Example Output

```text
Enter the number guessed: 5
Guess a higher number

Enter the number guessed: 8
Guess a lower number

Enter the number guessed: 7
Correct number guessed!
```

## Concepts Used

* `random` module
* `random.randint()`
* `input()` function
* `if-elif-else` statements
* `while` loop
* `break` statement

## License

This project is licensed under the MIT License. See the LICENSE file for details.

