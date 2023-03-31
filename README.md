# TicTacToe_MiniMaxAlgorithm


This program is a console-based Tic Tac Toe game implemented in Python. The program allows for two modes of play: single-player mode against a computer opponent that uses the Minimax algorithm to make its moves and two-player mode in which two players take turns playing on the same board. 

#Importing Libraries 
This program imports the random library, which is used in the function to choose whether the computer player should play as X or O. 

#Functions 
The program includes the following functions: 
•	print_board(board): Prints the current state of the Tic Tac Toe board. 
•	check_win(board, player): Determines if a given player has won the game. 
•	check_draw(board): Determines if the game has ended in a draw. 
•	get_move(board, player): Gets the move for the player in two-player mode. 
•	get_computer_move(board, computer_player): Gets the move for the computer player in single-player mode. 
•	get_other_player(player): Returns the symbol of the other player given the symbol of one player. 
•	minimax(board, is_maximizing, computer_player): Calculates the optimal move for the computer player using the Min-Max algorithm. 
•	play_single_player(): Implements the logic for single-player mode. 
•	play_two_player(): Implements the logic for two-player mode.  

#How the Program Works? 

Game board: The game board is represented as a list of three lists, each containing three strings representing the state of each square on the board. The strings are either " ", "X", or "O", depending on whether the square is empty or has been marked by a player. 

Game modes: The program supports two modes of play: single-player mode and two-player mode. 
1.	Single-Player Mode: In single-player mode, the player plays against the computer, which uses the Min-Max algorithm to make its moves. The algorithm considers all possible moves and their outcomes recursively to determine the best move to make. 
2.	Two-Player Mode: In two-player mode, two players take turns making moves on the same board until a player wins or the game ends in a draw. 

Game logic: The game logic is implemented in two functions, play_single_player() and play_two_player(), which handle the flow of the game depending on the chosen mode of play. 

•	In single-player mode, the game starts with the computer player randomly choosing whether to play as "X" or "O". The board is then initialized, and the game proceeds with the computer player and the user taking turns making moves. If a player wins or the game ends in a draw, the game ends. 
•	In two-player mode, the board is initialized, and the game proceeds with the two players taking turns making moves. If a player wins or the game ends in a draw, the game ends.
