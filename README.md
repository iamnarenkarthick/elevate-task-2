# elevate-task-2
Python Tic-Tac-Toe game

Python Tic-Tac-Toe Game
Welcome to the Python Tic-Tac-Toe Game repository! This project is a simple and interactive implementation of the classic Tic-Tac-Toe game, built using Python and the Tkinter library.

Features
Two-player mode: Players take turns marking their moves on the grid.
Simple GUI: User-friendly interface with buttons representing the game grid.
Win detection: Automatically checks for winning conditions and announces the winner.
Draw detection: Identifies when the game is a tie and resets the board.
Board reset: Automatically resets the board after a game ends.
Getting Started
Prerequisites
Python 3.x
Tkinter library (usually comes pre-installed with Python)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/iamnarenkarthick/elevate-task-2.git
cd elevate-task-2
Run the game:

bash
Copy code
python tic_tac_toe.py
How to Play
Launch the game by running the tic_tac_toe.py file.
The game board will appear with a 3x3 grid of buttons.
Players take turns clicking on the buttons to mark their moves ('X' and 'O').
The game will detect and announce the winner when a player gets three marks in a row, column, or diagonal.
If the grid is filled without any winning condition, the game will announce a draw.
The board will reset automatically after a win or a draw.
Code Explanation
check_winner(board, player): Checks if the specified player has won the game.
is_full(board): Checks if the game board is full.
on_click(row, col): Handles the click event for the buttons, updates the board, checks for a win or draw, and switches players.
reset_board(): Resets the game board for a new game.
Project Structure
tic_tac_toe.py: The main script that runs the game.
README.md: This readme file.
Future Improvements
AI opponent: Implement a computer opponent with varying difficulty levels.
Score tracking: Keep track of scores across multiple games.
Improved UI: Enhance the user interface for a more modern look and feel.
Contributing
Contributions are welcome! If you have any ideas for improvements or encounter any bugs, feel free to open an issue or submit a pull request.

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request
