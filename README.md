# minesweeper-react
The classic minesweeper Game built in ReactJs

This project template was built with Create React App, which provides a simple way to start React projects with no build configuration needed.

How to run Minesweeper project:

git clone https://github.com/raul-kmr/minesweeper-react.git

cd minesweeper-react

npm install

npm start

Rules of the Game

1. The minesweeper board is a 8 x 8 square. We could make it other sizes, like the classic Windows version, but for demonstration purposes we will stick to the smaller, “beginner” version of the game.

2.The board has a predetermined number of randomly placed mines. The player cannot see them.

3. Cells can exist in one of two states: opened or closed. Clicking on a cell opens it. If a mine was lurking there, the game ends in failure. If there is no mine in the cell, but there are mines in one or more of its neighboring cells, then the opened cell shows the neighboring mine count. When none of the cell’s neighbors are mined, each one of those cells is opened automatically.

4. Right clicking on a cell marks it with a flag. The flag indicates that the player knows there is a mine lurking there.

5. The player wins the game if he/she opens all cells without mines.
