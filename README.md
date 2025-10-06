# Hangman Game 🎯

A simple **Hangman** game implemented in Python. Guess the hidden word one letter at a time before running out of attempts!

---

## Table of Contents

- [Overview](#overview)  
- [How to Play](#how-to-play)  
- [Features](#features)  
- [Code Explanation](#code-explanation)  
- [Usage](#usage)  
- [Extending the Game](#extending-the-game)  
- [License](#license)  

---

## Overview

This is a classic word guessing game called **Hangman**, where the player tries to guess the letters in a hidden word. The player has a limited number of incorrect guesses before the game ends.

The game selects a random word from a predefined list and prompts the player to guess letters. Correct guesses reveal the letters in the word; wrong guesses reduce the remaining attempts.

---

## How to Play

1. The game randomly selects a word.
2. The player guesses one letter at a time.
3. If the letter is in the word, it will be revealed in the correct positions.
4. If the letter is not in the word, the player loses an attempt.
5. The game continues until the player guesses the entire word or runs out of attempts.

---

## Features

- Random word selection from a predefined list
- Input validation (only single alphabet letters allowed)
- Keeps track of guessed letters to avoid repeats
- Displays current state of the word with underscores for unguessed letters
- Shows the number of remaining attempts
- Friendly prompts and messages

---

## Code Explanation

- The word is randomly chosen using `random.choice()`.
- A list of underscores (`_`) represents unguessed letters.
- Player inputs are checked for validity.
- Correct guesses update the displayed word.
- Incorrect guesses decrease the number of attempts.
- The game ends with a win or lose message.

---

## Usage

1. Make sure you have Python 3 installed.
2. Save the `hangman.py` file (or your script file).
3. Run the script in your terminal or command prompt:

```bash
python hangman.py
