

# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a classic Hangman game in Python. Practice string manipulation, loops, conditionals, and random selection by creating a word-guessing game where players try to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️	Create the Hangman Game

#### Description
Write a Python program that lets a player guess letters to uncover a hidden word. The game should randomly select a word from a list, track the player's guesses, and display progress after each guess.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list
- Accept single-letter guesses from the user
- Show the current progress (e.g., _ _ a _ _ a _)
- Track and display the number of incorrect guesses remaining
- End the game when the word is fully guessed or attempts are exhausted
- Display a win or lose message at the end

Example:
```text
Word: _ _ n _ m _ n
Guess a letter: a
Word: _ a n _ m a n
Guess a letter: g
Word: g a n _ m a n
...etc.
```

### 🛠️	Enhance the Game (Optional)

#### Description
Add extra features to make your Hangman game more fun or user-friendly.

#### Requirements
Completed program could:

- Show letters already guessed
- Allow the player to play again without restarting the program
- Use a larger or themed word list
- Add simple ASCII art for the hangman
