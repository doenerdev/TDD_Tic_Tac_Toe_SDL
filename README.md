# TDD_Tic_Tac_Toe_SDL

## Requirement
Business wants to build a simple tic tac toe game for the command line.

The game is played on a 3x3 grid by two players in alternating turns. Each player can put one mark in a an unoccupied field during their turn (Player 1: X | Player 2: O). When a player has reached 3 of their marks in a row - horizontally, vertically or diagonally - the game has ended and said player has won the game. As a bonus, the game should also end if the grid state is such that the game must inevitably end in a draw.


## Notes
This exercise isn't intended to be finished within the given time! Try to focus on the TDD cycle and break down the given problem space into smaller chunks. Iteratively build up the feature set. Also remember about writing a test or todo list first.

- The (visual) output and input of the game can be ignored and only be used for debugging purposes for now
- Mabye ignore the game loop and player turns at first and focus on the grid rules and the win condition(s).
- Player input can be simulated, for example like this: "x01" for placing a mark ("X") for Player 1 at grid positon x:0|y:1 or "o22" for placing a mark ("O") for Player 2 at grid position x:2|y:2.
 
