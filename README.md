# Hangman_Game
![image](https://github.com/mshoeb7/Hangman_Game/assets/107172641/32dabb82-29dc-428c-83cf-efb852f2d6eb)


## Project Overview  
### Description of the Hangman Game  
-***Game setup***: The game of hangman is for two or more players, comprising a selecting player and one or more guessing players.
-***Word selection***: The selecting player selects a word that the guessing players will try to guess.
              -The selected word is traditionally represented as a series of underscores for each letter in the word.
              -The selecting player also draws a scaffold to hold the hangman illustration.
-***Guessing***: The guessing players attempt to guess the word by selecting letters one at a time.
-***Feedback***: The selecting player indicates whether each guessed letter appears in the word.
            -If the letter appears, then the selecting player replaces each underscore with the letter as it appears in the word.
            -If the letter doesn’t appear, then the selecting player writes the letter in a list of guessed letters. Then, they draw the next piece of the hanged man. To draw the hanged man, they begin with the head, then the torso, the arms, and the legs for a total of six parts.
-***Winning conditions***: The selecting player wins if the hanged man drawing is complete after six incorrect guesses, in which case the game is over. The guessing players win if they guess the word.
           -If the guess is right, the game is over, and the guessing players win.
           -If the guess is wrong, the game continues.
           
To write the hangman game in Python, we’ll make a few additional design decisions:
1) The game will be between the computer and one human player.
2) The computer will act as the selecting player and will select the word to guess, process human input, and handle all output.
3) The human player is the guessing player, hereafter simply referred to as the player. When the player knows the word, they continue to guess the correct letters until the word is complete.
