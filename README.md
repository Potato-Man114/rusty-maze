# Rusty Maze

## Requirements

1. Automatically Generated Maze
    1. 20 x 30
1. Player starts at a random position

1. Goal position is at a different random position
    1. At least 5 moves away from the player

## Design

1. Game struct
    - Knowledge of Maze structure
1. Maze struct
    - Walls and cells
1. Wall struct (entity)
    - knows the index of both cells that it effects
1. Cell struct
    - Knows whether it has been travelled to
    - Knows whether it is the goal or not

TODO: setup screen structure, follow bevy menu example.