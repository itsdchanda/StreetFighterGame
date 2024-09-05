
# Java Street Fighter Game

## Overview
The **Java Street Fighter Game** is a simple 2D fighting game developed in Java. It provides a fun way to explore concepts such as Object-Oriented Programming (OOP), Game Programming, and Exception Handling. The game features basic player animations, collision detection, and game effects, making it a great learning project for Java developers interested in game development.

## Features
- **Player Movement and Combat Mechanics:** Control the player with simple movement keys and perform attacks.
- **Animation and Effects:** Basic animations for characters during movement and combat.
- **Collision Detection:** Determine when characters land hits on each other.
- **Health and Score Display:** Each player’s health and current score is displayed on the screen.
- **Reset Mechanism:** The game can be reset by pressing a designated key.

## Game Rules
- Two players face off in a simple fighting arena.
- Each player can move left, right, jump, and perform attacks.
- The objective is to reduce the opponent’s health to zero.
- The game ends when one player’s health is fully depleted.

## Controls
- **Player 1:**
  - **W/A/S/D:** Move up, left, down, and right.
  - **Space:** Jump
  - **J:** Punch
  - **K:** Kick
- **Player 2:**
  - **Arrow Keys:** Move up, left, down, and right.
  - **Numpad 0:** Punch
  - **Numpad 1:** Kick

## How to Run the Game
1. Clone the repository using the following command:
    ```bash
    git clone https://github.com/yourusername/JavaStreetFighterGame.git
    ```
2. Open the project in a Java IDE such as VS Code or Eclipse.
3. Compile and run the `StreetFighterGame` class.
4. Enjoy the game!

## Code Snippets

### Example of Collision Detection

```java
public boolean checkCollision(Player player1, Player player2) {
    Rectangle player1Bounds = player1.getBounds();
    Rectangle player2Bounds = player2.getBounds();
    return player1Bounds.intersects(player2Bounds);
}
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
