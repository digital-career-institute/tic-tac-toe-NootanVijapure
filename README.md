# tic-tac-toe

# guidelines
Understanding the Game Logic:

-Familiarize yourself with the rules of Tic-Tac-Toe. Understand the grid, winning conditions (horizontal, vertical, diagonal), and the concept of turns for 'X' and 'O'.
Setup the Board:

-Create a 3x3 grid structure to represent the Tic-Tac-Toe board. This could be done using a 2D array, where each cell represents a position on the board.
Display the Board:

-Write a method to display the current state of the board after every move. Use ASCII art or simple text to represent the board and its contents ('X', 'O', or empty spaces).
Player Input:

-Implement user input handling to allow players to input their moves. Accept input for the row and column from the user to place their respective 'X' or 'O' on the board.
Check for Valid Moves:

-Validate user inputs. Ensure that the chosen position on the board is empty and within the board's bounds. If the position is already occupied or out of range, prompt the user for a valid input.
Check for a Winner:

-Create a method to check for a winner after each move. Examine the board to determine if any player has fulfilled the winning conditions. This includes checking rows, columns, and diagonals for three consecutive 'X' or 'O' symbols.
