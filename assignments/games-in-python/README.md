# 🎮 Hangman Game Challenge

## Objective

Build the classic word-guessing game using Python strings, loops, and user input. This assignment will help you practice string manipulation, loops, conditionals, and random selection.

## Tasks

### Task 1: Game Setup
**Description**: Create a Python program that initializes the Hangman game.
**Requirements**:
- Define a predefined list of words for the game.
- Randomly select a word from the list for each game session.

### Task 2: Player Interaction
**Description**: Implement user input to allow players to guess letters.
**Requirements**:
- Accept letter guesses from the player.
- Display the current progress of the word in `_ _ _` format.
- Track and display the number of incorrect guesses remaining.

### Task 3: Game Logic
**Description**: Add logic to determine the game's outcome.
**Requirements**:
- End the game when the word is guessed or attempts are exhausted.
- Display appropriate win/lose messages.

### Task 4: Bonus Features (Optional)
**Description**: Enhance the game with additional features.
**Requirements**:
- Allow players to play multiple rounds without restarting the program.
- Add a scoring system to track player performance.

## Example Input/Output

### Example 1: Winning the Game
```plaintext
Word: _ _ _ _
Guess a letter: e
Word: _ e _ _
Guess a letter: t
Word: t e _ t
Congratulations! You guessed the word: test
```

### Example 2: Losing the Game
```plaintext
Word: _ _ _ _
Guess a letter: x
Incorrect guesses remaining: 5
Guess a letter: z
Incorrect guesses remaining: 4
...
Game Over! The word was: test
```
