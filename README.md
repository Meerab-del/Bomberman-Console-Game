#  Bomber Man Game (C++ Console Game)

##  Overview
This is a console-based Bomber Man game developed in C++. It features grid-based gameplay with enemies, bombs, obstacles, and a scoring system. The game runs in two stages with increasing difficulty.

---

##  Features
- 2-stage gameplay system
- Player movement using arrow keys
- Bomb placement and timed explosions
- Enemy AI movement (random)
- Destructible & indestructible obstacles
- Score and lives system
- High score saving using file handling
- Colored console output (Windows API)

---

##  Controls
- Arrow Keys → Move Player
- B → Place Bomb
- Q → Quit Game

---

##  Concepts Used
- 2D Arrays (Grid-based game world)
- File Handling (High Score system)
- Game Loop design
- Collision detection
- Basic AI (Enemy movement)
- Timing logic (bomb explosion)
- Windows Console API (colors, cursor control)

---

##  Project Structure
- `main.cpp` → Game source code  
- `highscore.txt` → Stores top scores  

---

##  How to Run (VS Code)
1. Open project in **Visual Studio Code**
2. Install **C++ extension (Microsoft)**
3. Open `main.cpp`
4. Click **Run  button** OR use:
   - Ctrl + F5 (Run without debugging)
   - F5 (Run with debugging)

Make sure you are using **MinGW compiler (g++)** on Windows.

---

##  High Score System
- Stores top 3 scores in `highscore.txt`
- Automatically updates after game ends
- Displays ranking after game over

---

##  Author
Meerab Fatima
