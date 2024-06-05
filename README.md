The 2048 game is a single-player sliding block puzzle game. The objective of the game is to slide numbered tiles on a grid to combine them to create a tile with the number 2048. The game can be extended further to continue playing for higher numbers.

Game Logic
Grid: The game is played on a 4x4 grid.
Tiles: Each cell in the grid can hold a tile with a number that is a power of 2.
Moves: The player can move the tiles in four directions: up, down, left, or right. All tiles slide as far as possible in the chosen direction until they are stopped by either another tile or the edge of the grid.
Combining Tiles: If two tiles with the same number collide while moving, they will merge into a tile with the sum of their values. The resulting tile cannot merge with another tile in the same move.
New Tiles: After each move, a new tile (2 or 4) randomly appears in an empty spot on the board.
Winning: The player wins the game when they create a tile with the number 2048.
Losing: The player loses the game when no more moves are possible, i.e., when the grid is full and no adjacent tiles can be combined.
