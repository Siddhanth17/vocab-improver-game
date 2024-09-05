# Random Word Guessing Game
Welcome to the **Random Word Guessing Game**! This Python program will test your vocabulary and guessing skills by giving you a random word with missing letters. You'll need to guess the word correctly before running out of lives.


## API Information
- Random words are fetched from: [Random Word API](https://random-word-api.herokuapp.com/word)
- Word meanings are fetched from: [Free Dictionary API](https://dictionaryapi.dev/)


## Features
- Retrieves a random word from an API
- Displays the word with alternating letters hidden
- Provides the meaning of the word to help with guessing
- Gives you 3 chances to guess the word correctly
- Fun feedback when you win or lose!


## How It Works
1. The game fetches a random word from the [Random Word API](https://random-word-api.herokuapp.com/word).
2. It fetches the word's definition from the [Free Dictionary API](https://dictionaryapi.dev/).
3. The word is displayed with every second letter hidden (`_`).
4. The meaning of the word is displayed to help you.
5. You have 3 chances to guess the word.
6. If you guess the word correctly within the given chances, you win. Otherwise, the correct word is revealed after you run out of lives.

## How to Run
1. Copy the code to your local machine.
2. Run the Python file:
3. Follow the on-screen instructions to play the game.

## Future Improvements
- Add a graphical interface (GUI) for a better gaming experience.
- Allow difficulty levels with more challenging words.
- Track scores across multiple rounds.

### Enjoy the game and improve your vocabulary!