# Week 4: Final Bug Fixes & Stability Report

The following issues were identified and resolved during the final stabilization phase:

| Bug Identified | Fix Implemented | Impact |
| :--- | :--- | :--- |
| **Screen Flickering** | Replaced `system("cls")` with `SetConsoleCursorPosition`. | Improved visual stability and user experience. |
| **Invalid Food Spawn** | Added a collision check loop in `placeFood()`. | Food no longer spawns on the snake's body. |
| **Self-Collision Logic** | Fixed pointer traversal to check all body nodes. | Game now accurately ends when the snake hits itself. |
| **Memory Leakage** | Properly implemented `delete` in the `removeTail` function. | Ensured no dangling pointers or memory leaks during runtime. |
| **Input Lag** | Optimized `_kbhit()` and `Sleep()` intervals. | Movement response is now more fluid and predictable. |
