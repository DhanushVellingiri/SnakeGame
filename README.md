# Snake Game

A classic Snake game implemented in Python using the Pygame library.

## Features
- Move the snake using arrow keys.
- Eat food to grow longer.
- Avoid colliding with the walls and yourself.
- Simple game loop with adjustable speed.

## Requirements
- Python 3.x
- Pygame library

## Installation
1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Install Pygame using pip:
   ```sh
   pip install pygame
   ```

## How to Play
1. Run the game script:
   ```sh
   python snake_game.py
   ```
2. Use the **Arrow Keys** to move the snake.
3. Eat the green square (food) to grow longer.
4. If the snake hits the wall or itself, the game is over.
5. Press **'C'** to play again or **'Q'** to quit when you lose.

## Game Controls
- **Arrow Keys**: Move the snake
- **C**: Restart game after losing
- **Q**: Quit game

## Code Structure
- `gameLoop()`: The main game loop handling events, movement, and rendering.
- `our_snake()`: Renders the snake on the screen.
- `message()`: Displays messages when the player loses.

## Future Improvements
- Add a scoring system.
- Implement different difficulty levels.
- Add sound effects and animations.
- Improve graphics with better UI.

## License
This project is licensed under the MIT License.

