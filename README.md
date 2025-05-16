# 🐍 Snake Game in C++ (Console Version)

This is a simple **Snake Game** implemented in **C++** using the console. It uses basic logic and rendering techniques to simulate the classic snake game, playable directly in the terminal window.

## 🎮 Features

* Move the snake using `W` (Up), `A` (Left), `S` (Down), `D` (Right)
* Eat the fruit (`F`) to grow your snake
* Game over if you hit the wall or yourself
* Real-time key inputs using `<conio.h>`

## 🧠 Game Logic

* The game initializes the snake in the center and places a random fruit on the board.
* Arrow keys are simulated using `WASD`.
* The snake grows with each fruit eaten and dies if it runs into walls or itself.
* Score increases by 10 with each fruit.

## 🛠️ Requirements

* A C++ compiler (e.g., g++, MSVC)
* Windows OS (for `<conio.h>` and `system("cls")`)
  *Note: This version uses `conio.h`, which is **non-standard** and **Windows-specific**.*

## 📦 How to Compile and Run

Using g++ on Windows:

```bash
g++ -o SnakeGame SnakeGame.cpp
./SnakeGame
```

## ⌨️ Controls

| Key | Action     |
| --- | ---------- |
| W   | Move Up    |
| A   | Move Left  |
| S   | Move Down  |
| D   | Move Right |
| X   | Exit Game  |

## 🧾 Sample Output

```
####################################################
#                                                  #
#                  F                               #
#                                                  #
#                     0                            #
#                                                  #
####################################################
SCORE: 10
```

## 📁 Code Structure

* `Setup()`: Initializes game variables
* `Draw()`: Renders the game board
* `Input()`: Captures and processes keyboard input
* `Logic()`: Updates game logic, snake movement, collision detection

## 🚧 Limitations

* Only works on Windows (due to use of `<conio.h>` and `system("cls")`)
* No cross-platform support
* No timing control — the snake moves only when keys are pressed

## 🧑‍💻 Author

This game was created as a fun console project to practice basic C++ programming, game loops, and real-time input handling.

---
