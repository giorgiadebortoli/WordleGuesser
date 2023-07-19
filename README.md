# WordleGuesser
Introducing the Wordle Guesser: a Python code using entropy &amp; info theory. Makes intelligent guesses by calculating entropy of words in a wordlist. Picks low entropy words for higher accuracy. Elevates chances of finding the target word in the limited attempts of the game.


This Python code is designed to assist players in the popular word game Wordle by generating intelligent guesses based on entropy and information theory principles. Wordle is a game where players try to guess a five-letter word given limited feedback on each guess. This program uses a wordlist as its input and employs an entropy-based strategy to make educated guesses.

The code starts by loading a dictionary of valid words from a wordlist file. When run, it prompts the user to enter the feedback received from previous guesses, where 'x' represents a correct letter in the correct position, and 'o' indicates a correct letter in the wrong position.

Using the feedback provided, the program calculates the entropy of each word in the dictionary. Words with higher entropy are more uncertain and less likely to be the target word, while those with lower entropy are more likely candidates. The program then selects a word with the lowest entropy as the next guess, maximizing the potential information gain.

This entropy-based approach enables the guesser to make strategic choices, increasing the chances of correctly guessing the target word within the limited number of allowed attempts in Wordle. By leveraging information theory, the program provides an intelligent and efficient method to assist players in this challenging word game.
