# Snake Game in Java

## Overview

A simple Snake Game built using Java Swing and AWT. The player controls a snake that grows in length by eating food while avoiding collisions with the walls and its own body.

## Features

* Real-time snake movement
* Keyboard controls (Arrow Keys)
* Random food generation
* Score tracking
* Collision detection
* Game Over screen
* Built using Java Swing GUI

## Technologies Used

* Java
* Java Swing
* Java AWT

## Project Structure

```text
SnakeGame.java
GamePanel.java
```

### SnakeGame.java

* Application entry point
* Creates the game window
* Initializes the game panel

### GamePanel.java

* Handles game logic
* Snake movement
* Food generation
* Collision detection
* Score tracking
* Rendering graphics

## Controls

| Key | Action     |
| --- | ---------- |
| ↑   | Move Up    |
| ↓   | Move Down  |
| ←   | Move Left  |
| →   | Move Right |

## How to Run

1. Compile the files:

```bash
javac SnakeGame.java GamePanel.java
```

2. Run the game:

```bash
java SnakeGame
```

## Gameplay

* Guide the snake to eat food.
* Each food item increases the score and snake length.
* Avoid hitting the walls.
* Avoid colliding with the snake's own body.
* The game ends when a collision occurs.

## Future Improvements

* Pause and Resume functionality
* High score system
* Sound effects
* Difficulty levels
* Restart button
* Enhanced graphics

## Author

Developed as a Java Swing project for learning game development fundamentals and event-driven programming.
