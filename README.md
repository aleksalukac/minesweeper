
# Minesweeper

You can try to play this game at [aleksa.lukac.rs/minesweeper](http://aleksa.lukac.rs/minesweeper)

## Gameplay:

To start the game just open the index.html file.
After your first click on the board, the board will generate and each cell will have 15% of containing a mine (while the cell that you clicked first will not containt a mine). 
Every other cell will containt a number of mines in its neighbourhood (0 (empty cell) to maximum 8). You can eather dig the cell or place a flag on it (you can choose your action on the two buttons on the top).
If you try to dig an opened cell that has at least 1 mine in its neighbourhood, and if you have put exactly that number of flags in its neighbourhood, you will automaticaly dig all the
unopened cells in its neighbourhood (like in the original game with the middle mouse click).
The game is finished either when you dig a mine (you lose), or when all the free cells are opened.
