# Hangman_game
Overview:
This Python project is a complete implementation of the classic Hangman word-guessing game. It uses basic Python features—functions, loops, conditional logic, and simple data structures—to create an interactive command-line experience.

Features:
This Hangman project is a robust, command-line implementation of the classic word game, demonstrating several foundational Python programming features:
1. Visual Progression and Graphics:-
The project's most distinct feature is the inclusion of ASCII art graphics to represent the hangman figure.
2.External Word Dictionary:-
The project uses a standard practice for robust word games by separating the data (word list) from the code (logic).
3. Efficient Guess Tracking:-
The project utilizes the appropriate Python data structure for efficient tracking of player guesses.
4. Main Game Loop and Flow:-
The game's structure ensures a smooth, repetitive, and controlled playing experience

Technologies and tools used:
The project relies entirely on Core Python Language Features and its Standard Library:
Core Python Features
Data Structures:
Lists (for stages and the masked word display).
Sets (for guessed_letters).
Control Flow:
while Loops (for the game turns and continuous play).
if/else statements (for evaluating guesses and checking win/loss conditions).
for Loops (for revealing all instances of a correctly guessed letter).
Functions: Used for modularity (get_word() and hangman()).
String Manipulation: Used for handling user input (.lower()) and formatting the output (' '.join(display)).
Python Standard Library Modules
random Module: Used to select the secret word randomly from the list.
File I/O: Used with open() and read() to access the word data in words.txt.
Exception Handling: Provided by the try...except block.

STEPS TO INSTALL AND RUN THIS PROJECT:
Since this project is entirely based on Core Python and a simple text file, installation and running it is straightforward.
1. Project Setup (Creating the Files)
You only need two files for this project: the Python code file and the word dictionary file.

Create the Python File:

Open a text editor (like VS Code, Sublime Text, or Notepad++).

Copy and paste the entire Python code you provided into this new file.

Save the file as hangman_game.py.

Create the Word Dictionary File:

Create a second new text file in the same folder as hangman_game.py.

Save this file as words.txt.

Populate this file with words, ensuring each word
⚙️ Tips to Install and Run the Hangman Python Project
Since this project is entirely based on Core Python and a simple text file, installation and running it is straightforward. Here are the step-by-step tips to get the game running on your system.

1. 📂 Project Setup (Creating the Files)
You only need two files for this project: the Python code file and the word dictionary file.

Create the Python File:

Open a text editor (like VS Code, Sublime Text, or Notepad++).

Copy and paste the entire Python code you provided into this new file.

Save the file as hangman_game.py.

Create the Word Dictionary File:

Create a second new text file in the same folder as hangman_game.py.

Save this file as words.txt.

Populate this file with words, ensuring each word is on a separate line. The program relies on line breaks to read each word correctly.

Tip: Keep the words simple and in lowercase to avoid case-sensitivity issues, as the code converts the user's guess to lowercase but expects the words in the file to match the case of the guess for the game to work correctly.

2. Environment and Execution
You need to have the Python interpreter installed on your machine to run the script.

Verify Python Installation:

Open your command line interface (Terminal on macOS/Linux, Command Prompt/PowerShell on Windows).

Type the following command and press Enter:

Bash

python --version
If you see a version number (e.g., Python 3.9.5), you're ready to go!

Run the Project:

Use the cd command in your terminal to navigate to the folder where you saved your two files (hangman_game.py and words.txt).

Execute the script using the Python interpreter:

Bash

python hangman_game.py
Start Playing:

The program will immediately prompt you: "Do you want to play Hangman? (y/n): "

Enter y or yes to begin guessing letters!

