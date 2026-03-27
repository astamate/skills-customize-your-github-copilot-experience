
# 📘 Assignment: Games in Python

## 🎯 Objective

Build a classic Hangman word-guessing game using Python strings, loops, and user input. Create a game where players guess letters to reveal a hidden word before running out of attempts.

## 📝 Tasks

### 🛠️	Set Up Game Components

#### Description
Initialize the game with a word list, choose a random word, and set up initial game state including variables for tracking guesses and attempts.

#### Requirements
Completed program should:

- Create a predefined list of words for the game
- Randomly select a word from the list
- Initialize variables for guessed letters, remaining attempts, and game progress


### 🛠️	Display Game Progress

#### Description
Show the current state of the word with blanks for unguessed letters and display remaining attempts to the player.

#### Requirements
Completed program should:

- Display the word in _ _ _ format showing only correctly guessed letters
- Show the number of remaining attempts
- Update the display after each guess


### 🛠️	Handle Player Guesses

#### Description
Accept letter input from the player, validate the input, and update the game state based on whether the guess is correct or incorrect.

#### Requirements
Completed program should:

- Accept single letter input from the player
- Check if the letter is in the hidden word
- Add correct guesses to the revealed letters
- Decrease remaining attempts for incorrect guesses
- Prevent guessing the same letter twice


### 🛠️	Implement Win/Lose Logic

#### Description
Check for win or lose conditions after each guess and display appropriate messages to end the game.

#### Requirements
Completed program should:

- Check if all letters in the word have been guessed (win condition)
- Check if attempts have been exhausted (lose condition)
- Display a win message showing the complete word
- Display a lose message revealing the hidden word
