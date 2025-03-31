# Python Snake Game 🐍🎮
## Peace Samuel

### Introduction
This is a simple Snake game implemented in Python using the `turtle` module. The project serves as a learning exercise for game development concepts and working with the `turtle` graphics library in Python. The game features a snake that moves around the screen, consuming 'food' to grow in length, and ends if the snake collides with the screen border or itself.

### Features
- Move the snake using arrow keys
- Randomly placed food items
- Increasing score and snake length as food is eaten
- Collision detection for walls and self
- Scoreboard display
- Simple game over screen

### How to Play
1. Run the Python script.
2. Use the **arrow keys** to control the movement of the snake.
3. Eat the white squares (food) to grow and increase your score.
4. Avoid hitting the borders or yourself.
5. The game ends when you collide with the border or your own body, displaying the final score.

### Installation and Requirements
#### Prerequisites
Ensure you have Python installed on your system. The game uses the built-in `turtle`, `random`, and `time` modules, so no external libraries are needed.

#### Running the Game
1. Clone or download this repository.
2. Open a terminal or command prompt.
3. Navigate to the folder containing the script.
4. Run the script using:
   ```bash
   python snake_game.py
   ```

### Skills Involved
This project covers various Python programming skills and concepts, including:

#### 1. **Game Development Concepts**
- Managing game loops and frame updates
- Handling user input (keyboard events)
- Implementing object movement and collision detection

#### 2. **Python `turtle` Module**
- Creating and manipulating graphical elements using `turtle`
- Drawing and moving objects on a Cartesian coordinate system
- Changing colors, shapes, and pen behavior for custom graphics

### 3. **Data Structures and Logic**
- Using lists to track snake body segments
- Implementing conditional statements for movement logic
- Managing object positions and interactions

#### 4. **Basic Animation and Timing**
- Using `screen.update()` for rendering updates
- Controlling game speed using `time.sleep()`
- Animating movement by redrawing objects at new positions

### Future Improvements
- Add difficulty levels with adjustable speed
- Implement a restart feature after game over
- Enhance graphics with custom sprites instead of `turtle` shapes
- Introduce sound effects for interactions
