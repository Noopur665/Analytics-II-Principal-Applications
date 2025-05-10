# Tic Tac Toe

This is a simple implementation of the classic Tic Tac Toe game in Python.

## How to Play

1.  Run the `play_game()` function.
2.  The game will print the current state of the board.
3.  Enter the row and column numbers (1-3) for your move when prompted.
4.  The game will alternate between players ("X" and "O").
5.  The game ends when one player gets three in a row (horizontally, vertically, or diagonally) or when the board is full (a tie).

## Functions

*   **`print_board(board)`:** Prints the current state of the board.
*   **`check_win(board, player)`:** Checks if the specified player has won.
*   **`play_game()`:** Handles the main game logic.

## Example Usage
This will start the game.
python play_game()

## How the code works:

**print_board(board):** This function prints the current state of the Tic Tac Toe board to the console.

**check_win(board, player):** This function checks if the specified player has won the game by examining rows, columns, and diagonals.

**play_game():** This function handles the main game logic, including player turns, input validation, win/tie conditions, and alternating between players.
