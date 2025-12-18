# Snake Game - Final Data Structures Project

## Project Overview
This is a classic Snake Game developed in C++ using the Singly Linked List data structure. The project demonstrates real-time data manipulation, where the snake's body dynamically grows and moves based on user input.

## Data Structures Implemented
* **Singly Linked List:** Used to manage the snake's body segments. 
    * **Nodes:** Each node stores the `(r, c)` coordinates of a body part.
    * **Head & Tail Pointers:** Used for O(1) efficiency in movement.
* **Search Algorithm:** A traversal-based search is used to detect collisions with the snake's own body.

## Key Features
* **Modular Design:** Code is divided into logical functions like `setup()`, `drawBoard()`, and `updateLogic()`.
* **Flicker-Free Rendering:** Optimized console output using Windows API cursor handling to prevent screen blinking.
* **Growth Logic:** The snake grows upon consuming food (`@`) by adding a head node without removing the tail.

## How to Run
1. Ensure you have a C++ compiler (like GCC/MinGW) installed.
2. Open your terminal and navigate to the `src` folder.
3. Compile the code: `g++ main.cpp -o SnakeGame`
4. Run the executable: `./SnakeGame`
5. **Controls:** Use `W` (Up), `S` (Down), `A` (Left), and `D` (Right).
