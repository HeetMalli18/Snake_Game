# Snake Game

## Overview
This is a classic Snake game implemented in C++ using the Windows console. The game features a growing snake that moves in four directions, eats food to grow, and avoids colliding with itself or the game boundaries. The game ends when the snake collides with the walls or itself.

## Features
- Console-based gameplay
- Responsive snake movement
- Collision detection with walls and itself
- Food spawning to increase score
- Dynamic game rendering using Windows console buffer

## Controls
- **W** - Move Up
- **S** - Move Down
- **A** - Move Left
- **D** - Move Right

## Requirements
- Windows OS (as it uses `windows.h` and `conio.h`)
- C++ Compiler (MinGW or MSVC recommended)

## How to Compile and Run
### Using MinGW (g++)
```sh
 g++ snake_game.cpp -o snake_game -std=c++11
 ./snake_game
```

### Using MSVC (cl)
```sh
 cl snake_game.cpp /Fe:snake_game.exe
 snake_game.exe
```

## Game Rules
1. The snake starts at a fixed position and moves in the last given direction.
2. The player can change the snake's direction using `W`, `A`, `S`, `D` keys.
3. The snake grows when it eats food, and the score increases.
4. The game ends if the snake collides with the walls or itself.
5. The final score is displayed upon game over.

## Code Structure
- `Point` Class: Represents coordinates on the board.
- `Snake` Class: Handles movement, growth, and direction changes.
- `Board` Class: Manages game logic, rendering, and food spawning.
- `main()` Function: Initializes the game loop and handles user input.

## Future Improvements
- Implement a high-score system.
- Add difficulty levels.
- Improve graphics using a better rendering method.
- Cross-platform support (removing Windows-specific dependencies).

## Contributors
- Heet Malli
- Om Vaghela
- Jainish Chaudhary
- Krish Paghdar

## License
This project is open-source and available under the MIT License.

