��
 
 1-100 Game
This is a simple number-guessing game called 1-100, implemented using HTML, CSS, and JavaScript.

Game Rules
The game randomly selects a number between 1 and 100.
The player needs to guess the correct number.
After each guess, the game provides feedback:
If the guessed number is higher, the message "Go lower!" is displayed.
If the guessed number is lower, the message "Go higher!" is displayed.
If the guessed number is correct, the message "Congratulations, you won!" is displayed.
The player has a limited number of attempts to guess the correct number.
If the player exhausts all the attempts without guessing the correct number, the message "Game over! You lost." is displayed.
File Structure
index.html: The HTML file that contains the game layout.
style.css: The CSS file for styling the game.
script.js: The JavaScript file containing the game logic.
Getting Started
To run the game, follow these steps:

Clone the repository or download the source code files.
Open index.html in a web browser.
Code Overview
index.html: The HTML file contains the structure of the game layout. It includes an input field for the player to enter their guesses, a button to submit the guess, and a message container to display the feedback messages.
style.css: The CSS file provides basic styling for the game elements, such as centering the game layout, adjusting font sizes, and adding some colors.
script.js: The JavaScript file handles the game logic. It generates a random number, listens for the player's guesses, checks the validity of the guesses, provides feedback, and determines the game outcome.
Game Logic
The game logic implemented in script.js is as follows:

Generate a random number between 1 and 100 using Math.random().
Store the random number in a variable.
Listen for the player's guesses when the submit button is clicked.
Validate the input guess to ensure it is a number between 1 and 100.
Compare the player's guess with the random number:
If the guess is higher, display "Go lower!" message.
If the guess is lower, display "Go higher!" message.
If the guess is correct, display "Congratulations, you won!" message.
If the player has used all the attempts, display "Game over! You lost." message.
Update the attempt count after each guess.
Reset the game when the player wins or loses.
Feel free to modify the code, customize the styling, or enhance the game further according to your requirements.

Enjoy playing the 1-100 game!
