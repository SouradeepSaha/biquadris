# Biquadris

## Motivation

Biquadris is the latinization of the game of Tetris: where two players take turns to drop blocks on the board and points are awarded when a complete bottom row is cleared. This game was written in C++ and tested with valgrind in collaboration with Alex Tse and Raymond Zhu as part of the CS246 final project at the University of Waterloo.

## Gameplay

### Overview
Each user takes turns to drop their block on the screen. Command is taken input via the command line and output is displayed via the command line as well as a X11 graphicdisplay. 

### Available Commands
- left: moves the current block one cell left, if possible
- right: moves the current block one cell right, if possible
- down: moves the current block one cell down, if possible
- clockwise: rotates the block 90 degrees clockwise, if possible
- anticlockwise: rotates the block 90 degrees counterclockwise, if possible
- drop: drop the current block to the board
- levelup: increases the level (difficulty) of current player by 1
- leveldown: decreases the level (difficulty) of current player by 1
- norandom file: takes the blocks from the file labelled as file
- random: restores randomness in levels 3 and 4
- sequence file: executes commands found in file
- I,J,L,T,S,Z,O : changes current block to input block
- restart: restarts the game

### Command line arguments
- -text: runs the game in textonly mode
- -seed x: sets the random seed generator to x
- -startlevel n: sets starting level of game to n
- -scriptfile1 filename: uses filename as source of blocks for level0, player1
- -scriptfile2 filename: uses filename as source of blocks for level0, player2

## Demo
![Biquadris-Graphic](https://github.com/SouradeepSaha/biquadris/blob/main/biquadrisGraphic.gif)
![Biquadris-Command-line](https://github.com/SouradeepSaha/biquadris/blob/main/biquadrisCmdLine.gif)
