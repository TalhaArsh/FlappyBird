# Flappy Bird Console Game

A console-based implementation of the popular Flappy Bird game using C++. The game features basic bird movement, pipe obstacles, and a score-tracking system. 

## How to Play

- **Controls**:
  - Press `Spacebar` to make the bird jump.
  - Press `Esc` to exit the game.
  
- **Objective**:
  - Control the bird and avoid the pipes.
  - Each time you pass through the pipes, your score increases.

## Features

- A bird represented by ASCII art.
- Randomly generated pipe positions.
- Collision detection with pipes.
- Score system based on how many pipes the bird successfully flies through.
- Instructions menu and game-over screen.

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/flappy-bird-console-game.git
   ```

2. Compile the code:
   ```bash
   g++ flappy_bird.cpp -o flappy_bird
   ```

3. Run the game:
   ```bash
   ./flappy_bird
   ```

## Instructions

- Once you run the game, you will be presented with a menu:
  1. Start Game - Begin a new game.
  2. Instructions - View the instructions on how to play.
  3. Quit - Exit the game.

- During gameplay, press `Spacebar` to make the bird jump. Avoid hitting the pipes or the ground. If you collide with any obstacle, the game ends.

- Press `Esc` at any time during the game to exit.

## Dependencies

- Windows console application
- Standard C++ libraries (`iostream`, `conio.h`, `Windows.h`, etc.)

## Game Screen

- The game features a simple interface where the bird (represented by `/--o\\`) flies through gaps in pipes. The pipes are displayed as vertical lines, and the score is shown on the right side of the screen.

## How the Game Works

- Pipes are generated randomly, and the bird has to pass through the gap between them.
- The player controls the bird's position using the `Spacebar`, causing the bird to jump upwards. Gravity pulls the bird downwards.
- The game ends when the bird hits a pipe or the ground.

## Code Overview

The project consists of a single `main.cpp` file containing the following components:

- **Game Logic**: Handles bird movement, pipe generation, and score updates.
- **Collision Detection**: Checks whether the bird collides with the pipes or the ground.
- **Rendering**: Draws the bird, pipes, and other UI elements on the console window.

## Future Enhancements

- Adding a high score system.
- Improving collision detection for more precise gameplay.
- Adding sound effects for jumping and game over events.

## License

This project is licensed under the MIT License.

## Acknowledgements

Inspired by the original Flappy Bird game.
```

### Explanation:

- **Introduction**: A brief description of the game and its mechanics.
- **Installation**: Steps to set up and run the game.
- **Controls**: How to control the bird in the game.
- **Features**: Summary of the game’s core features.
- **Code Overview**: Explains how the game works under the hood.
- **Future Enhancements**: Suggestions for improving the game.
