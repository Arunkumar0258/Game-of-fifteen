# Game-of-fifteen

A mind-blowing puzzle game, commonly known as the "Game of Fifteen". 
This version is updated to support any board between 3x3 to 9x9.

The empty tile is represented by 0. And you can type any number adjacent to the empty tile (0) and the empty tile will
move accordingly. The goal is to reverse the entire board or flip it.

As a extra feature, all your moves are logged into a file named log, which you can refer later to review your mistakes.
The game also automatically refreshes after every move. This is done using the C ANSI Escape Sequences.

To quit the game, at any point, press 0 and enter

Usage: ./fifteen <number>

where <number> is any number between 3 to 9, corresponding to the nxn board to play with.
