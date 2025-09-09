### Simon Says Game

This is a digital version of the classic memory game "Simon Says." The game challenges players to repeat a progressively longer sequence of flashing colors and sounds.

#### How to Play

1.  Open the `simon.html` file in your web browser.
2.  The game will display "Press any key to start the game".
3.  Press any key on your keyboard to begin.
4.  The game will flash one of the four colored buttons.
5.  Click on the button that flashed.
6.  As you advance, the game will add a new button to the sequence. Your task is to remember and repeat the entire sequence in the correct order.
7.  If you make a mistake, the screen will flash red, and the game will end.
8.  Your final score, which corresponds to the level you reached, will be displayed. You can press any key to start a new game.

#### Project Files

* **`simon.html`**: The main structure of the game's user interface. It contains the game title, instructions, and the four interactive colored buttons. It also links to the CSS and JavaScript files.
* **`simon.css`**: This file handles all the styling for the game. It defines the appearance of the buttons, the layout, and the special visual effects for when a button is flashed or pressed.
* **`simon.js`**: This file contains the core game logic. It initializes the game, manages the game sequence and the user's sequence, and includes functions for:
    * **`btnFlash`**: Flashes a button white to indicate it's part of the game sequence.
    * **`userFlash`**: Flashes a button green when the user clicks on it.
    * **`levelUp`**: Advances the game to the next level by adding a random color to the game sequence.
    * **`checkAns`**: Compares the user's sequence with the game's sequence to check for a correct answer or a game over condition.
