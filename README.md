Quiz Game with Hangman Visual Feedback
Overview
This program is a simple console-based quiz game written in C. The user is asked a series of random questions, and they must answer correctly within a limited number of attempts. The game includes a "hangman"-style visual feedback system to represent the remaining chances.

Features
Random Question Selection: Each round, a question is randomly selected from a predefined set.
Multiple Chances: The user has 4 chances to answer each question correctly.
Visual Feedback: As the user gets the answer wrong, a simple hangman visual representation is displayed.
Replay Option: After answering a question correctly, the user can choose to play again or end the game.
Prerequisites
A C compiler (e.g., GCC).
Basic knowledge of C programming to understand and run the program.
Gameplay Instructions
The program will randomly select a question and display it on the screen.
The player needs to type the answer and press Enter.
If the answer is correct, the player is congratulated and asked if they want to play again.
If the answer is incorrect, the player will be given up to 4 chances, with a visual hangman representation showing the remaining chances.
If all chances are used up, the game will display a game-over message and end.
Exiting the Game
After answering a question correctly, the program will prompt whether the user wants to continue. Enter 1 to continue playing, or any other number to exit the game.
If the user fails to answer a question within 4 chances, the game will end automatically.
Code Explanation
Array of Questions and Answers: The program uses a 2D array b[][2] to store pairs of questions and their corresponding answers.
Random Selection: rand() % 12 is used to randomly select one of the 12 questions.
User Input: The program uses scanf() to read the user's answer and compares it to the correct answer using strcmp().
Hangman Visual: A simple text-based hangman figure is displayed as the user makes wrong guesses.
Notes
The game currently has a fixed set of 12 questions. You can modify the b array to add or change questions.
The answer comparison is case-sensitive. Ensure that the user's input matches the expected case of the correct answer.
License
This program is open-source and free to use, modify, and distribute. No specific license is applied.

Enjoy the game and feel free to customize it according to your needs!
