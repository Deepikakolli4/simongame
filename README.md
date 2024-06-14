#  Simon Game
This is a web-based implementation of the classic Simon game. The game tests the player's memory by generating a sequence of colors that the player must reproduce. The sequence gets progressively longer and more complex as the game continues.

# Table of Contents
## Simon Game
### Table of Contents
#### Overview
->Game Rules
->Installation
->Usage
->Code Structure
->Technologies Used
->Contributing
____________________________________________________________________________________________________________________________________________________________________________________________________________________
## Overview
The Simon Game is a fun and challenging game that helps improve memory and concentration. The game consists of four colored buttons (red, green, yellow, blue). The game will light up these buttons in a random sequence, and the player must replicate the sequence. Each round, the sequence gets longer, making it more difficult to remember.

## Game Rules
Start the Game: Press any key or click on the screen to start the game.
Watch the Sequence: The game will highlight a sequence of colors.
Repeat the Sequence: Click the buttons in the same order as the highlighted sequence.
Continue: If you successfully repeat the sequence, the game will add another color to the sequence and repeat the process.
Game Over: If you click the wrong button, the game will end, and you can restart by pressing any key or clicking the screen.

## Installation
To run the Simon Game locally, follow these steps:

Clone the Repository:
Copy code
git clone https://github.com/your-username/simon-game.git
Navigate to the Project Directory:

Copy code
cd simon-game
Open index.html in Your Browser:
Simply open the index.html file in any modern web browser to start playing the game.

## Usage
Once you have the game running in your browser:

Press any key or click on the screen to start the game.
Watch the sequence of colors displayed.
Click the buttons to replicate the sequence.
If you make a mistake, the game will display "Game Over" and prompt you to restart.

## Code Structure
The project's file structure is as follows:

graphql
Copy code
simon-game/
│
├── index.html      # The main HTML file
├── styles.css      # CSS for styling the game
└── main.js         # JavaScript file containing game logic
HTML (index.html)
Contains the structure of the game, including buttons for each color and the main header.

CSS (styles.css)
Provides styling for the game, including colors, layout, and animations for the buttons.

JavaScript (main.js)
Implements the game logic, including generating sequences, handling user input, playing sounds, and updating the game state.

JavaScript Code Breakdown
Global Variables:

started, level, gamePattern, userPattern, colours
Event Handlers:

$(document).on("keypress", ...): Starts the game on key press.
$(document).on("click", ...): Starts the game on click.
$(button).on("click", ...): Handles button clicks to capture user input.
Functions:

checkAnswer(currentLevel): Checks if the user's input matches the game pattern.
generateSequence(): Generates the next sequence in the game.
playSound(colour): Plays the sound corresponding to a color.
startOver(): Resets the game state.
animatePress(userChoice): Animates button presses.
Technologies Used
HTML5: For the structure of the web page.
CSS3: For styling the game elements.
JavaScript: For game logic and interactivity.
jQuery: For simplifying DOM manipulation and event handling.
Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

Fork the Repository: Click the "Fork" button at the top of this page.
Clone the Forked Repository:
Copy code
git clone https://github.com/your-username/simon-game.git
Create a New Branch:
Copy code
git checkout -b feature/your-feature-name
Make Your Changes: Implement your feature or fix the bug.
Commit Your Changes:
Copy code
git commit -m "Add your commit message here"
Push to Your Branch:
Copy code
git push origin feature/your-feature-name
Open a Pull Request: Submit your pull request with a detailed description of your changes.

# VIDEO SAMPLE
https://github.com/Deepikakolli4/simongame/assets/165411615/48e60e31-c326-42e8-9e40-5c78e5778e5e
