# 🐀 Rat in a Maze – Interactive Backtracking Visualizer  


An interactive Java Swing application that visualizes the classic **Rat in a Maze** problem solved via **backtracking**. Users can draw their own maze, start the solver, and watch the algorithm explore and highlight every valid path from the start (top‑left) to the destination (bottom‑right) cell.

---

## ✨ Features

- 🖱️ **Interactive Grid Editor** – Click to toggle walls (0 = blocked, 1 = open).  
- ▶️ **Step‑by‑Step Animation** – Visualizes each recursive step of the backtracking algorithm.  
- 🏁 **Path Highlighting** – Shows every successful route found, or notifies if no path exists.  
- 🔄 **Reset & Randomize** – Quickly reset or generate random mazes for fresh challenges.  
- 🎓 **Educational Overlay** – Displays current (row, col) and call‑stack depth for learning purposes.  

---

## 🧠 Algorithm Overview

1. **Start at (0, 0).**  
2. Explore moves **Down (D), Right (R), Up (U), Left (L)** in that order (or customizable).  
3. Mark visited cells to avoid cycles.  
4. On reaching the destination, record the path and continue (to find all paths).  
5. Visual updates occur at each recursion step to illustrate exploration and backtracking.

---

## 🖼️ Screenshots

![Screenshot 2025-06-20 183853](https://github.com/user-attachments/assets/e6772727-df8e-43b2-aadc-dc5c552c46cb)
![Screenshot 2025-06-20 183911](https://github.com/user-attachments/assets/5e94cae8-1cb3-4f6c-9185-2b4153df2c9a)



---

## 🛠️ Tech Stack

- **Language:** Java 17 (or above)  
- **UI:** Java Swing, AWT, Graphics2D  
- **Paradigm:** Backtracking / Recursion  
- **Build / Run:** `javac` & `java` CLI or any Java IDE (IntelliJ, Eclipse, VS Code)

---

## 🚀 Setup & Run

```bash
# Clone the repository
git clone https://github.com/your-username/rat-in-a-maze-visualizer.git
cd rat-in-a-maze-visualizer

# Compile
javac RatInAMaze.java

# Run
java RatInAMaze
```

The GUI window will open.  
- **Left‑click** to toggle cells.  
- Press **Start** to begin visualization.  
- Press **Reset** to clear the grid or **Randomize** for a new maze.

---

## 👤 Author

**Afjan Jamadar**  


---

## 📝 Note

This project demonstrates how recursive backtracking explores solution space while providing real‑time visual feedback — a powerful aid for teaching algorithms and problem‑solving.
