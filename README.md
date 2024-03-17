# HANGMAN-GAME-PROJECT

Project Title: Hangman Game

Description:
The Hangman Game is a classic word-guessing game where one player thinks of a word and the other player(s) try to guess it by suggesting letters within a certain number of attempts.
It's a fun and interactive way to challenge vocabulary and guessing skills. This project is a digital implementation of the traditional pen-and-paper game, allowing users to play it on a computer or mobile device.

Team members:
Navya : 2310990749,

Aastha Sahi: 2310991407,

Nishant Verma: 2310990753.

Instructions for Playing Hangman:
Objective: The objective of the game is to guess the hidden word before running out of attempts.

Starting the Game: When you start the game, you'll see a message welcoming you to Hangman.

Guessing the Word: You'll be presented with a series of underscores, each representing a letter in the hidden word. You need to guess letters one at a time to uncover the word.

Guessing Letters: Enter a single letter as your guess and press Enter. The game will tell you if the letter you guessed is in the word or not.

Correct Guesses: If your guessed letter is in the word, it will be revealed in the appropriate position(s) in the word.
Incorrect Guesses: If your guessed letter is not in the word, the game will deduct one attempt from your total attempts remaining.

Remaining Attempts: You start with 5 attempts. Each incorrect guess reduces your attempts by 1.

Winning: If you correctly guess all the letters in the word before running out of attempts, you win! The game will congratulate you and reveal the hidden word.

Losing: If you run out of attempts before guessing the word correctly, the game ends, and it will reveal the hidden word.

Playing Again: After the game ends, you'll be asked if you want to play again. If you choose "yes," the game will start again with a new hidden word. If you choose "no," the game will end with a thank you message.;


EDITION 1: EDITION-1 contains code without GUI . It is simple python code. Error handling in the code is minimal, primarily focusing on checking if the user input was a single letter. It has limited replayability.

EDITION-2: EDITION-2 contains a little better version of 1st Edition like The 2nd EDITION provides a graphical user interface (GUI) for the Hangman game, which enhances the user experience compared to the text-based interface of the 1st edition but the interface in Edition 2 lacks visual appeal due to the absence of background colors or any visual styling. While error handling is present in Edition 2, the feedback provided to the user for invalid inputs or duplicate guesses is limited to a single warning message box.

EDITION-3: Edition 3 is the improvisation of edition 2 like a better version of GUI but Edition 3 of the game lacks visual appeal due to the absence of color and visual elements. The interface appears dull and could potentially reduce player engagement.It has minimal interactivity beyond entering guesses. This could make the gameplay feel static and less engaging for players. While error handling is present in Edition 3, the feedback provided for invalid guesses is limited, potentially leading to confusion for players.

EDITION-4: The EDITION-4 is better than other edition because it provides a more interactive and visually appealing Hangman game interface. It prevents duplicate guesses and ensures that only single alphabetic characters are accepted as valid guesses. It enhances interactivity by providing hints when the player has only three guesses left. This additional feature adds strategy to the gameplay and keeps players more engaged. It utilizes the canvas widget to dynamically draw the hangman figure as incorrect guesses are made. Edition 4 refactors the code into a class-based structure, improving readability and maintainability. It separates concerns more effectively, making the codebase easier to understand and extend.
