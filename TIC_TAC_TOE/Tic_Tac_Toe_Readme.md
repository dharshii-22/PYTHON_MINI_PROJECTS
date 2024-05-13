## Tic Tac Toe Game

This Python program implements a simple text-based Tic Tac Toe game. Players can play against the computer, which makes its moves based on a simple algorithm. The game continues until the player decides to stop playing.

### Libraries Used
- **os** 🖥️: Provides a way to interact with the operating system to clear the screen.
- **random** 🎲: Used for generating random moves for the computer player.

### Methods
- **insertLetter(letter,pos)**: Inserts a letter ('X' or 'O') at the specified position on the board.
- **spaceIsFree(pos)**: Checks if the specified position on the board is empty.
- **printBoard(board)**: Prints the current state of the board.
- **isBoardFull(board)**: Checks if the board is full.
- **IsWinner(b,l)**: Checks if a player has won the game.
- **playerMove()**: Allows the player to make a move.
- **computerMove()**: Determines the computer's move.
- **selectRandom(li)**: Selects a random move from a list of possible moves.
- **StartTheGame()**: Starts a new game.
- **CleanScreen()**: Clears the screen.
- **TieGame()**: Checks if the game has ended in a tie.

### How to Play
1. Run the program.
2. Enter a number between 1 and 9 to place your '❌' on the Tic Tac Toe board.
3. The computer will place its '⭕' on the board.
4. The game continues until there is a winner, a tie, or the player decides to stop playing.

### Sample Output 
![image](https://github.com/dharshii-22/PYTHON_MINI_PROJECTS/assets/110839215/725984e6-198c-4090-b197-0e3d04da8dbe)
