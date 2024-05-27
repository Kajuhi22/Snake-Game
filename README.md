**Challanges Faced** :

 -Creating my own  version of snake game based on the given source code.

 -importing the nessesory modules  
 -setting up required jdk
 
 -Changing color of score to random.
 - modifying the shape of snake .
 - changing color of snake head.
 - Using nessesory dimensions.
    
    
**Description** :
Creating a Snake game in Java involves using a graphical library such as Swing to handle the GUI components and the game loop.
Components
- **GameFrame**: The main window that contains the game panel.
- **GamePanel**: The main game area where the snake moves and interacts with food.
- **Snake**: The player-controlled object that grows when it eats food.
- **Food**: The item the snake must eat to grow.
- Defined:
- 1. **GameFrame**: The main window for the game. It creates and displays the `GamePanel`.
2. **GamePanel**: The core of the game. It handles drawing the snake and food, updating the game state, and handling user input.
3. **Snake Movement**: Managed by the `move` method, which updates the position of the snake's body parts based on the current direction.
4. **Food Collision**: The `checkFood` method checks if the snake has eaten the food, increasing the snake's size and relocating the food.
5. **Self-Collision and Wall Collision**: The `checkCollision` method ensures the game ends if the snake collides with itself or the wall.

6. **Score** it is used to give the no. of food that the snake ate.
7. The game box is aligned to center
8. Jframe is required
9. On collision the game over will pop up / display .

    **Programmed By** `Pranai`
