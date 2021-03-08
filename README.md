# Tetris-Clone
This is a clone of the classic video game Tetris. The purpose behind this is to create a controlled environment for a soon-to-be-developed Tetris AI. Information about my implementation of the game is listed below.

## Controls
- ESC - Quit the Game
- Z - Rotate Piece
- X - Drop Piece
- Left, Right, Down - Move Piece in Inputted Direction

## Game Pieces
Each game piece is represented by a 5 x 5 integer grid. Each piece is comprised of 4 blocks where each block is represented by a non-zero integer. In the grid, a zero indicates an empty space; a one indicates a segment of a game piece; a two indicates a pivot point of a game piece. The pivot point is the segment where each piece rotates clockwise. There are 7 game pieces: I, L, mirrored-L, N, mirrored-N, square, and T
