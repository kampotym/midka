**TIC TAC TOE GAME**

![2024-12-10_00-53-57](https://github.com/user-attachments/assets/eae9616d-c57f-4978-bea3-183e39297ced)



**Project Goal:**

The goal of this project is to create a simple and interactive Tic Tac Toe game using HTML, CSS, and JavaScript. The game allows two players to take turns playing the classic Tic Tac Toe game on a 3x3 grid. Players alternate placing their marks ('X' or 'O') on the grid, and the first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins the game. The game also tracks and displays the score for each player and allows users to restart the game.

**How the Game Works:**

1. Start the Game:

When the game loads, the welcome message appears, and the 3x3 grid is ready for players to start playing.
Player X always goes first, followed by player O.
Making a Move:

2. Players click on any empty cell of the grid to place their mark ('X' or 'O').
The current player’s mark is displayed inside the cell.
The game alternates between Player X and Player O after each valid move.
Checking for a Winner:

3. After every move, the game checks if there is a winner by looking for three matching marks in a row, either horizontally, vertically, or diagonally.
If there is a winner, a notification appears at the top of the screen displaying "Player X wins!" or "Player O wins!". The winner's score is updated.
Handling a Draw:

4. If all cells are filled and there is no winner, a "Draw!" notification appears.
Restarting the Game:

5. After a winner is determined or in case of a draw, the game stops, and the player can click the "Restart" button to start a new game. The board is cleared, and the game resets to its initial state.
Tracking the Score:

6. The score for each player (X and O) is displayed below the game board and is updated after each round.
How to Play:

**Open the game in a browser.**
Click on the empty cells in the 3x3 grid to place your mark.
Alternate between Player X and Player O until one player wins or the game ends in a draw.
The game automatically displays a winner or a draw and updates the scores.
Click the "Restart" button to start a new round.


1. **Introduction to JavaScript**: The project uses JavaScript to implement the game logic, such as handling clicks, determining the winner, and restarting the game.

2. **Use of Notification Functions and console.log**:
   - A notification is displayed when a player wins (via the `showNotification` function).
   - The game logic uses JavaScript to show messages about the win or a draw, which could also include the use of `console.log` (although `console.log` is not used in this code, it can be added for debugging).

3. **Variables and Data Types**:
   - Variables like `currentPlayer`, `boardState`, `gameActive`, and `score` are used to manage the state of the game.
   - Data types such as strings, arrays, and objects are used for storing and processing information.

4. **Conditional Statements (if-else)**:
   - In the `handleCellClick` function, the `if` statement checks if a cell is already occupied or if the game has ended.
   - Conditional statements also check if there is a winner or if the game has ended in a draw.

5. **Loops (for, while, do-while)**:
   - The `forEach` loop is used to add event listeners to all the cells of the game board and update their content.
   - Other loops could be added in the future for performing additional checks or changes during gameplay.

6. **Functions (Declarations, Expressions, Arrow Functions)**:
   - All functions (such as `handleCellClick`, `checkWin`, `updateScoreboard`, and `restartGame`) are declared using the standard function syntax.
   - Arrow functions are also used, for example, to handle events in `cells.forEach`.

7. **Objects and Arrays**:
   - Objects (`score`) are used to track the players' scores.
   - Arrays (`boardState` and `winningConditions`) are used to store the game board state and possible winning conditions.

8. **Browser Events (Mouse and Keyboard Interactions)**:
   - Event listeners are used to track clicks on the game board cells and to restart the game.

9. **Document Manipulation (DOM Manipulation)**:
   - The code actively uses DOM to change the content of the page (for example, updating text and styles of cells, displaying notifications).





