# Tic Tac Toe Game

This repository contains a simple implementation of the classic Tic Tac Toe game in Python, with a focus on search algorithms in artificial intelligence.

### AI and Search
This implementation explores the concept of search algorithms in artificial intelligence, particularly utilizing the minimax algorithm to determine optimal moves for the computer player. The `minimax` function demonstrates the application of search algorithms in decision-making scenarios within the game. Feel free to explore and enjoy playing Tic Tac Toe with this AI-powered implementation!

## 1. tictactoe.py

### Overview
`tictactoe.py` defines the core game logic, including the state of the board, player turns, available actions, and the minimax algorithm for the computer player.

### Functions
- **initial_state():** Returns the starting state of the game board.
- **player(board):** Determines the player who has the next turn.
- **actions(board):** Returns a set of all possible actions available on the board.
- **result(board, action):** Returns the board that results from making a move on the current board.
- **winner(board):** Determines the winner of the game.
- **terminal(board):** Checks if the game is over.
- **utility(board):** Returns the utility value of the current board.
- **minimax(board):** Determines the optimal action for the current player using the minimax algorithm.

## 2. runner.py

### Overview
`runner.py` provides a graphical user interface (GUI) for playing Tic Tac Toe using the `pygame` library. It allows the user to choose between playing as "X" or "O" and provides a simple interface to make moves.

### Usage
1. Run `runner.py` to start the game.
2. Choose to play as "X" or "O" by clicking the corresponding button.
3. Click on the board to make your move.
4. If playing against the computer, wait for the computer's move.

### Additional Features
- The game displays the winner or a tie when the game is over.
- Option to play again after a game has ended.

