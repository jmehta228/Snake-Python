# Snake-Python

## Overview
This is a simple implementation of the classic Snake game using the **Pygame** library. The game involves controlling a snake to eat food that randomly spawns on the screen, causing the snake to grow in length. The player must avoid running into the snake’s own body or the walls of the game window.

## Features
- **Basic Snake Movement:** The snake can be controlled using the arrow keys (up, down, left, right).
- **Score Tracking:** The score increases by 10 each time the snake eats food.
- **Random Fruit Spawning:** The fruit spawns at random positions on the screen.
- **Collision Detection:** The game ends if the snake hits the walls or collides with its own body.
- **Game Over Screen:** Displays the player's score upon game over and then resets the game.
- **Fruit Spawning on Snake Body:** Ensures that the fruit does not spawn on the snake's body.

## How the Game Works
1. **Snake Initialization:** The snake starts with a position and a body consisting of several segments.
2. **Direction Control:** The snake moves in the direction set by the player (up, down, left, right).
3. **Fruit Consumption:** The snake eats fruit, which causes it to grow longer.
4. **Game Over Conditions:**
   - The snake hits the walls.
   - The snake collides with itself.
5. **Score Display:** The score is displayed at the top left of the screen.

## Code Explanation
- **Game Loop:** The main game loop listens for keyboard inputs and updates the snake's position. It checks for collisions with the walls and body and updates the score.
- **Fruit Spawning:** The fruit is placed randomly on the screen, ensuring it doesn’t spawn on the snake.
- **Game Over:** If a collision is detected, the game ends, and the player's score is shown.
