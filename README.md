
---

## 🧑‍💻 Programming Language Used & Why

### **Language: C**
I used **C language** because:

- It is the core programming language in our syllabus.
- C provides complete control over the logic and flow of the game.
- Functions like `rand()`, loops, and conditions help simulate a real dice roll and game steps.
- Helps build strong programming fundamentals.

---

## 📚 Libraries, Functions & Techniques Used

### **Header Files Used**
- `#include <stdio.h>` → Enables input/output functions (`printf`, `getchar`).
- `#include <stdlib.h>` → Provides `rand()` for dice rolling.
- `#include <time.h>` → Used for seeding random generator (`time(0)`).

### **Important Functions**
- **`rollDice()`** → Returns random value 1–6.
- **`checkSnakeOrLadder()`** → Identifies snake/ladder positions.
- **`srand(time(0))`** → Ensures different results each run.
- **`getchar()`** → Adds "Press ENTER to roll" interaction.

### **Techniques Used**
- Random number generation  
- Modular programming (separate functions)  
- Use of loops (`while`)  
- Conditional logic (`if/else`)  
- Realistic mapping of snakes and ladders  

---

## 🕹️ Project Features

- 🎲 Random dice generation  
- 🪜 Ladder climb detection  
- 🐍 Snake drop detection  
- ⛔ Exact 100 rule implemented  
- 📍 Live position updates  
- 🎮 Interactive ENTER-press gameplay  
- 🏁 Win detection with clear message  

---

## 🔧 How the System Works

1. Game starts at **position 1**.
2. User presses **ENTER** to roll the dice.
3. Dice value (1–6) updates the player's position.
4. If the new position is a **snake** → moves down.  
5. If it is a **ladder** → moves up.  
6. Player must reach **100 exactly** to win.
7. Loop continues until victory.

---

## ▶️ How to Compile & Run

### **Compile**
```bash
gcc snake_ladder.c -o snake_ladder
