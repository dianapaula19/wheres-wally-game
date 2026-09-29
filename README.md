# Where's Wally? Social Distancing Edition

> **Original version:** this README and some fixes were added in 2026. To see the project exactly as it was first built, browse commit [`3698db3`](https://github.com/dianapaula19/wheres-wally-game/tree/3698db343f22b1108fe30c8bcfa87dcb0922cb05) (2021-10-03).

A small point-and-click game drawn with legacy OpenGL and FreeGLUT: find Wally (red and white
stripes) among the masked, socially distanced crowd before your three lives run out. A wrong
click costs a heart, finding Wally draws a box around him, and a right click starts a new round.
The cloud drifts across the sky and the person on the left walks away from the crowd.

Made with [@andrardg](https://github.com/andrardg) for the *Computer Graphics* (OpenGL) course at
the University of Bucharest.

![Screenshot](docs/screenshot.png)

![Demo](wheres-wally-game-demo.gif)

## Build and run

```bash
sudo apt install freeglut3-dev      # Linux; on Windows use the freeglut binaries
g++ main.cpp -o wheres-wally -lglut -lGL -lGLU
./wheres-wally
```
