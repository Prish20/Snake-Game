# Snake Game

This is a simple implementation of the classic Snake game using Python's Turtle graphics module. The game involves a snake that moves around the screen, eating food to grow longer. The player controls the snake using the arrow keys, and the game ends if the snake collides with the wall or its own tail.

## Table of Contents

- [Game Description](#game-description)
- [Features](#features)
- [Python Concepts Learned](#python-concepts-learned)
- [Installation](#installation)
- [Usage](#usage)

## Game Description

In this game, the snake moves continuously in the direction it is facing. The player can change the direction of the snake using the arrow keys (Up, Down, Left, Right). The goal is to eat the food that appears at random positions on the screen. Each time the snake eats the food, it grows longer and the score increases. The game ends if the snake collides with the wall or its own tail.

## Features

- Snake movement control using arrow keys
- Randomly appearing food that the snake can eat to grow
- Score tracking
- Game over detection when the snake collides with the wall or its own tail

## Python Concepts Learned

### 1. **Modules and Imports**
   - Used `import` statements to include various modules such as `turtle`, `time`, and `random`.

### 2. **Object-Oriented Programming (OOP)**
   - Created classes to represent different components of the game:
     - `Snake`: Handles the creation and movement of the snake.
     - `Food`: Handles the creation and random positioning of the food.
     - `Scoreboard`: Handles the score display and game over message.

### 3. **Inheritance**
   - Used inheritance to extend the functionality of the `Turtle` class for `Snake`, `Food`, and `Scoreboard` classes.

### 4. **Methods and Functions**
   - Defined methods within classes to encapsulate functionality, such as movement control, collision detection, and score updating.

### 5. **Event Handling**
   - Used the `screen.onkey` method to handle key press events for controlling the snake.

### 6. **Screen Updates and Game Loop**
   - Used `screen.tracer(0)` and `screen.update()` for manual control of screen updates.
   - Implemented a game loop using a `while` loop to continuously update the game state.

### 7. **Random Module**
   - Utilized the `random` module to generate random positions for the food.

## Installation

To run this game, you need to have Python installed on your system. The game relies on the Turtle graphics library, which is included in the standard Python library.

1. Clone the repository or download the source code.
2. Navigate to the project directory.

## Usage

Run the game by executing the `main.py` script:

```sh
python3 main.py
