# 📘 Assignment: Hangman Game

## 🎯 Objective

Build a word-guessing game using Python strings, loops, conditionals, and user input. Practice tracking game state and responding to a player's guesses.

## 📝 Tasks

### 🛠️ Set Up the Game

#### Description
Complete the starter code to select a secret word and initialize the variables needed to track the game.

#### Requirements
Completed program should:

- Randomly select one word from the provided `words` list.
- Start with no guessed letters and no incorrect guesses.
- Allow the player up to 6 incorrect guesses.


### 🛠️ Play a Round of Hangman

#### Description
Implement the game loop so the player can guess letters, see their progress, and find out whether they won or ran out of attempts.

#### Requirements
Completed program should:

- Display each letter in the secret word when guessed and an underscore for each letter not yet guessed.
- Prompt the player for one letter at a time and handle guesses without treating uppercase and lowercase letters differently.
- Track and display the number of incorrect guesses remaining.
- End the game when the player guesses the word or uses all 6 incorrect guesses.
- Display a win message for a correctly guessed word, or a lose message that reveals the secret word.
