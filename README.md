# Flappy Bird Java

This is a simple Flappy Bird game clone implemented in Java using Swing for the graphical user interface. The game involves navigating a bird through a series of pipes without colliding with them.

## Features

- **Graphics**: The game uses simple 2D graphics to render the bird, pipes, and background.
- **Game Mechanics**: The bird moves upwards when the spacebar is pressed and falls due to gravity. Pipes move from right to left, and the player scores points by successfully passing through them.
- **Collision Detection**: The game detects collisions between the bird and pipes, ending the game if a collision occurs.
- **Score Tracking**: The player's score is displayed on the screen, and the game ends with a "Game Over" message showing the final score.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- An IDE or text editor for Java development (e.g., IntelliJ IDEA, Eclipse, VSCode)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Nipuna-Lakruwan/Flappy-Bird-Java.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Flappy-Bird-Java/Flappy\ Bird\ Game/src
   ```

3. **Run the application**:
   ```bash
   java App
   ```

### Project Structure

  - App.java: This is the entry point of the application. It sets up the main game window and initializes the FlappyBird game panel.
  - FlappyBird.java: This file contains the main game logic, including rendering graphics, handling user input, and managing game state.


### How to Play 

  - Press the spacebar to make the bird jump.
  - Avoid hitting the pipes as they move across the screen.
  - The game ends when the bird collides with a pipe or the ground.
  - Your score increases by 1 for each set of pipes you pass.


## Assets

The game uses the following image assets:

  - flappybirdbg.png: Background image
  - flappybird.png: Bird image
  - toppipe.png: Image for the top pipes
  - bottompipe.png: Image for the bottom pipes

Ensure these images are located in the same directory as the compiled Java files for the game to load them correctly.

### License

This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as you wish.

### Acknowledgments 

  - Inspired by the original Flappy Bird game.
  - Developed by Nipuna Lakruwan.

For any questions or contributions, please feel free to reach out or submit a pull request.
