# Hangman Game

Word guessing game "**Hangman**" - implemented on Ruby. 
About the game: https://en.wikipedia.org/wiki/Hangman_(game)

**Rules:** 
- The computer guesses the word
- The player tries to guess it letter by letter
- If the player guessed the letter that is in the word, it opens
- If the player did not guess the letter, he is given an error
- If the word is guessed completely, player wins
- If the player made a mistake more than the set limit (7 mistakes) - player lost

**How to lauch:**

Install ruby and run on command line
`ruby main.rb`

**About files:** 

main.rb - main programm file
lib/game.rb - a class that describes logic of the game
lib/console_interface.rb - a class designed to display current game status
data/figures - files with graphics that display status of the game
data/words.txt - a file with a list of words from which the computer chooses randomly to play
