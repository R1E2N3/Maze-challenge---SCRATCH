# Maze-challenge - SCRATCH
A game that I developed for kids to engage in CS classes.

## How the maze generation works
The game is developed on Scratch and its main functionality is to generate a new random maze every time you solve it. It works by using the "pen" package from Scratch to draw a new rectangle until the whole screen is filled. To implement it, you draw a new rectangle and then rotate the direction by a random multiple of 90˚, then you change custom to a square that has half the width of the rectangle and check where it can move, you then move it in that direction, if he has nowhere to move (i.e., all four  directions are covered) then you move back until it has a way to go and draw another rectangle there at some point it'll fill the whole screen and will go back to the beginning at which point I display the maze and start the game.

## Limitations
- It works best for tile sizes larger than 20 pixels.

- It takes some time to render the maze, the smaller the tile size, the larger the time it takes to render.
