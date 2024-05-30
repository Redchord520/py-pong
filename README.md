# Atari Pong Game Recreation using Turtle Graphics

## Description

This project recreates the classic Atari game Pong using Python's Turtle graphics library. The game is designed using object-oriented programming (OOP) principles, with separate modules for the scoreboard, ball, and paddles.

## Features

- **Scoreboard**: Displays the game score.
- **Ball**: Handles the ball's movement and collision detection.
- **Paddles**: Manages the movement of the left and right paddles.
- **Collision Detection**: Includes:
  - Top and bottom wall collisions.
  - Paddle collisions.
  - Right paddle miss.
  - Left paddle miss.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Redchord520/py-pong.git
    cd py-pong
    ```

2. Ensure you have Python installed. The Turtle graphics library is included with Python's standard library, so no additional installation is necessary.

## Usage

1. Run the main script:
    ```bash
    python main.py
    ```

2. Game Controls:
    - Right Player: Up and Down arrow keys.
    - Left Player: W and S keys.

## File Structure

- `main.py`: The main script to set up the screen and create game objects.
- `scoreboard.py`: Manages the display of the game score.
- `ball.py`: Controls the ball's movement and handles collisions.
- `paddle.py`: Manages paddle movements for both players.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

Special thanks to the creators of the original Atari Pong game, Angela Yu's Python Bootcamp, and the contributors of the Turtle graphics library.

