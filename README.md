# Epic Relocation - A Flappy Bird Inspired Game

Welcome to **Epic Relocation**! This is a fun and addictive game inspired by the classic Flappy Bird. Control your fish, avoid obstacles, and see how far you can go! The game is built using JavaScript and the p5.js library.

---

## How to Play

- **Spacebar** or **Mouse Click**: Flap your fish's wings to keep it in the air.
- **Avoid Obstacles**: Dodge the pipes and waves to survive.
- **Score Points**: Earn points by flying further. Can you beat your best score?

---

## Features

- **Dynamic Obstacles**: Randomly generated pipes and waves to keep the game challenging.
- **Score Tracking**: Track your current score and best score.
- **Responsive Design**: The game adapts to your screen size for the best experience.
- **Music and Sound Effects**: Enjoy background music and sound effects for an immersive experience.

---

## Code Overview

The game is built using JavaScript and the p5.js library. Here's a brief overview of the code structure:

### Key Variables
- `GRAVITY`: Controls the downward force on the fish.
- `FLAP`: Controls the upward force when the fish flaps.
- `fish`, `pipes`, `waves`: Sprites for the fish and obstacles.
- `score`, `bestscore`: Track the player's score and best score.

### Functions
- **`setup()`**: Initializes the game, loads assets, and sets up the canvas.
- **`draw()`**: The main game loop. Handles rendering, collision detection, and game logic.
- **`newGame()`**: Resets the game state for a new round.
- **`die()`**: Handles the game-over state and resets the game.

### Game Logic
- The fish's position is updated based on gravity and player input.
- Obstacles (pipes and waves) are randomly generated and move towards the fish.
- Collision detection checks if the fish hits an obstacle or the ground.
- The score increases as the fish survives longer.

---

## Dependencies

- [p5.js](https://p5js.org/): A JavaScript library for creative coding.
- [p5.sound.js](https://p5js.org/reference/#/libraries/p5.sound): For playing background music and sound effects.
