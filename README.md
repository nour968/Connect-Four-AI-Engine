# 🎮 Connect Four AI

A classic **Connect Four** game developed in **Python** using **Pygame**, featuring an intelligent AI opponent powered by the **Minimax Algorithm** with **Alpha-Beta Pruning**.

The project demonstrates how game theory and artificial intelligence can be applied to create strategic gameplay while maintaining an enjoyable user experience.

---

## ✨ Features

- 🎲 Classic Connect Four gameplay
- 🤖 AI opponent using Minimax Algorithm
- ⚡ Alpha-Beta Pruning for faster decision making
- 🎯 Smart board evaluation and scoring
- 🎨 Interactive graphical interface with Pygame
- 🎮 Mouse-based gameplay
- 🔀 Randomized AI moves for more natural gameplay
- 🏆 Automatic win detection
- 📊 Strategic move evaluation

---

## 📸 Gameplay
https://github.com/user-attachments/assets/df22528a-3d79-4487-a7f4-c0aebb0dadab


---
## 🛠️ Technologies Used

- Python 3
- Pygame
- NumPy

---

## 🧠 AI Implementation

The computer opponent uses:

- **Minimax Algorithm**
- **Alpha-Beta Pruning**
- Board evaluation heuristic
- Center-column preference
- Offensive and defensive move scoring
- Adjustable search depth

The AI evaluates possible future moves and selects the move with the highest expected score while pruning unnecessary branches to improve performance.

---

## 📂 Project Structure

```
Connect-Four-AI/
│
├── connect_four.py
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Connect-Four-AI.git
```

### 2. Navigate to the project

```bash
cd Connect-Four-AI
```

### 3. Install dependencies

```bash
pip install pygame numpy
```

### 4. Run the game

```bash
python connect_four.py
```

---

## 🎮 How to Play

- The **Red** pieces represent the human player.
- The **Yellow** pieces represent the AI.
- Click on a column to drop your piece.
- Players alternate turns.
- The first player to connect **four pieces** horizontally, vertically, or diagonally wins.

---

## ⚙️ Game Configuration

You can modify several parameters inside the code:

| Parameter | Description |
|-----------|-------------|
| `AI_DEPTH` | AI search depth |
| `ROW_COUNT` | Number of rows |
| `COLUMN_COUNT` | Number of columns |
| `WINDOW_LENGTH` | Number of connected pieces required for evaluation |

Increasing `AI_DEPTH` makes the AI stronger but increases computation time.



## 🚀 Future Improvements

- Multiple difficulty levels
- Player vs Player mode
- Scoreboard
- Sound effects and background music
- Game restart button
- Move animations
- Undo functionality
- Better AI heuristics
- Online multiplayer

---

## 📚 Concepts Demonstrated

- Artificial Intelligence
- Game Theory
- Minimax Search
- Alpha-Beta Pruning
- Heuristic Evaluation
- Event-Driven Programming
- Object-Oriented Programming
- Graphical User Interfaces

---

## 👨‍💻 Author

Developed as an educational project demonstrating AI-based decision making in games using Python and Pygame.

---

⭐ If you found this project helpful, consider giving it a star!
