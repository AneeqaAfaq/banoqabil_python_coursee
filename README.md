Word Selection:

The game starts by randomly selecting a word from a predefined list.
GUI Elements:

The main window includes labels to display the current state of the word being guessed and the number of attempts remaining.
An entry field allows the player to input a single letter for their guess.
"Guess" and "Reset" buttons enable the player to submit a guess and start a new game, respectively.
A canvas is used to draw the hangman figure as the game progresses.
Game Logic:

Players guess one letter at a time.
If the guessed letter is in the word, it gets revealed in the display.
Incorrect guesses result in deductions from the available attempts, and the hangman figure is drawn part by part on the canvas.
The game continues until the player either correctly guesses the word or runs out of attempts.
End of Game:

If the player successfully guesses the word, a congratulatory message is displayed.
If the player runs out of attempts without guessing the word, a message reveals the correct word.
Resetting the Game:

After a game ends, the player can click the "Reset" button to start a new game with a new randomly selected word.
Overall Flow:

The game continuously runs in a loop, allowing the player to interact with the GUI until they decide to close the window.
In summary, the Hangman game built with Tkinter provides a graphical interface for players to guess letters and visually track their progress. The code includes functions to manage the game state, update the display, and handle user input.




