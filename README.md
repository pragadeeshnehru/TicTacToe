# TicTacToe

A simple TicTacToe game using Java.

# How is it done ?
1. The entire 3x3 matrix is first made empty
1. Player input is taken in terms of index values of a 3x3 matrix ( val1 + *space* + val2)
2. The displayboard() function is constatntly updated with values fed in by the players.
4. The haveWon() function checks three cases(rows, columns and diagonals) for similar matching.
5. If haveWon function returns true it updates the gameEnd (initially false) value then game ends and the current player is declared winner else the game continues.