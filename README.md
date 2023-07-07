# **Snake Game**

This is a simple Snake game implemented using Python's **`tkinter`** library. The game allows you to control a snake and eat food to grow longer. The objective is to eat as much food as possible without colliding with the walls or the snake's own body.

## **Prerequisites**

Before running the game, make sure you have the following requirements satisfied:

- Python 3.x installed on your system.
- The **`tkinter`** library is installed. This library is usually included in the standard Python installation.

## **How to Run**

To run the game, follow these steps:

1. Clone the repository or download the source code files.
2. Open a terminal or command prompt and navigate to the directory where the code is located.
3. Run the following command:
    
    ```
    python snake_game.py
    
    ```
    
4. The game window will appear, and you can start playing.

## **Gameplay**

- Use the arrow keys (up, down, left, right) to control the snake's direction.
- The snake will move continuously in the chosen direction.
- The objective is to eat the food that appears on the screen by moving the snake over it.
- Each time the snake eats food, it will grow longer.
- Avoid running into the walls or colliding with the snake's own body, as it will end the game.
- The score will be displayed at the top of the game window.

## **Customization**

You can modify certain aspects of the game by changing the following constants defined in the code:

- **`GAME_WIDTH`**: The width of the game window in pixels.
- **`GAME_HEIGHT`**: The height of the game window in pixels.
- **`SPEED`**: The speed of the snake's movement. Lower values make the game faster.
- **`SPACE_SIZE`**: The size of each square space on the game grid.
- **`BODY_PARTS`**: The initial number of body parts (segments) of the snake.
- **`SNAKE_COLOR`**: The color of the snake's body.
- **`FOOD_COLOR`**: The color of the food.
- **`BACKGROUND_COLOR`**: The background color of the game window.

Feel free to adjust these constants to customize the game according to your preferences.

## **Acknowledgements**

This Snake game was developed using the **`tkinter`** library in Python. It serves as a fun project for beginners and demonstrates the basics of game development with graphical interfaces.

## **License**

Feel free to use and modify the code as per your needs.
