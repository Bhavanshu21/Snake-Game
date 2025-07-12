#  Classic Snake Game in C++ (Console Version)

This is a classic **snake game** built using C++ that runs in the console. It includes both **killer walls** and **transparent wall** gameplay modes. You can move the snake using the `W`, `A`, `S`, `D` keys and collect fruits to grow the tail and increase your score.

---

 Features

-  **Killer vs Transparent Walls** mode
-  Random fruit generation (never on snake's body)
-  Tail grows when fruit is eaten
-  Game over if:
  - Snake hits itself
  - Hits wall (in killer mode)
-  Score tracking
-  Play again option on game over

---

 Controls

| Key | Action         |
|-----|----------------|
| `W` | Move Up        |
| `S` | Move Down      |
| `A` | Move Left      |
| `D` | Move Right     |
| `X` | Exit Game      |

---

##  How to Compile and Run

### On Windows:
1. Open terminal (CMD or PowerShell)
2. Compile using a C++ compiler (like MinGW):
   ```bash
   g++ -o snake_game snake.cpp
