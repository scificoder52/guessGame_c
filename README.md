# Number Guessing Game

Welcome to the **Number Guessing Game**! This simple command-line game challenges you to guess a randomly generated number between 1 and 100.

## How It Works

1. The game generates a random number between 1 and 100.
2. You will be prompted to guess the number.
3. After each guess, the game will provide feedback:
   - If your guess is too low, you'll be asked to guess a larger number.
   - If your guess is too high, you'll be asked to guess a smaller number.
   - If your guess is correct, the game will congratulate you and display the number of attempts it took to guess correctly.
4. The game will continue until you guess the correct number.

## Getting Started

### Prerequisites

To compile and run the game, you need a C compiler installed on your machine (e.g., GCC).

### Compilation

Compile the code using the following command in your terminal:

```bash
gcc -o guessing_game guessing_game.c
