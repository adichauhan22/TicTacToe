# TicTacToe
Tic-Tac-Toe Game

This program allows two players to play a game of Tic-Tac-Toe on the command line. It uses a 3x3 grid as the game board and determines the winner based on the traditional rules of Tic-Tac-Toe.

Instructions:


1. The game starts with an empty game board displayed on the screen.
2. Players take turns entering their moves. Each move consists of entering the row and column numbers where they want to place their symbol ('X' or 'O').
3. The row and column numbers should be entered as integers between 0 and 2, inclusive. For example, to place a symbol in the top-left cell, enter '0' for both row and column.
4. The game will check if the move is valid and update the game board accordingly.
5. The game will continue until one of the players wins or the game ends in a draw.
6. If a player wins, the program will display a message announcing the winner.
7. If the game ends in a draw, the program will display a message indicating that the game is a draw.
8. After the game ends, the final state of the game board will be displayed.
9. You can close the program by terminating the command line or terminal.

Enjoy playing Tic-Tac-Toe!

Code Explanation:

The code is organized into several methods to perform different tasks:

- The 'printBoard' method is used to display the current state of the game board on the screen.
- The 'haveWon' method checks if a player has won the game by examining the rows, columns, and diagonals of the game board.
- The 'main' method is the entry point of the program. It initializes the game board, prompts the players for their moves, updates the board, checks for a winner, and repeats the process until the game is over.
- The program uses a 2D character array to represent the game board, where each cell can hold either 'X', 'O', or a space character (' ') to indicate an empty cell.
- The program alternates between the two players, with 'X' starting first. It validates the moves entered by the players and prevents them from overwriting occupied cells.
- The game continues until a player wins or the game ends in a draw.
- The program uses the 'Scanner' class to read input from the command line or terminal.

Note: The code provided has been debugged and corrected to ensure it runs correctly.

Have fun playing Tic-Tac-Toe!
