# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a Hangman game that reinforces string handling, loops, and conditional logic while managing user guesses and game state.

## 📝 Tasks

### 🛠️ Word Selection and Setup

#### Description
Create the starting game state by choosing a random word from a predefined list and preparing the progress display.

#### Requirements
Completed program should:

- Randomly select a word from a list of at least 5 options.
- Initialize the hidden word display using underscores (for example: `_ _ _`).
- Set a fixed number of incorrect guesses allowed.

### 🛠️ Guessing Loop and End Conditions

#### Description
Implement the main game loop that accepts letter guesses, updates progress, tracks remaining attempts, and ends with a win or loss.

#### Requirements
Completed program should:

- Accept single-letter guesses from the user.
- Reveal correctly guessed letters in the progress display.
- Decrease remaining attempts on incorrect guesses.
- End the game when the word is fully revealed or attempts reach zero.
- Display a clear win or lose message.
