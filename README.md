# Battleship AI

## Project Details

Project under development.  
Battleship AI is made to find the optimal way to guess the position of ships in the game [Battleship](https://en.wikipedia.org/wiki/Battleship_(game)). The program takes into account the ships which are still floating and checks all the possible ways these ships could fit on the grid. Using that data, a probability heatmap is generated, which is used to target ships. The calculation updates after every shot. Ones it find a target, the program scans the area around it until the target is sunk.

Currently it takes 44 shots (median) to sinks all the ships. The goal is to reach 40 shots. Future plans are to include a CNN and grid state history in order to better guess the position of the ships.

## Requirements

`pip install numpy`  
`pip install matplotlib`