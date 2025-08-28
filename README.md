# ♟️ chess-ai

> A chess engine by someone who doesn't know how to play chess 😄  

---

## 📌 About

**chess-ai** is a simple chess AI built using **JavaScript**.

The primary focus of **chess-ai** is the **decision-making** logic of the AI.  
All other functionalities outside the scope of AI are implemented using external libraries:

- **Chessboard GUI:** [chessboard.js](https://chessboardjs.com/)
- **Game Mechanics:** [chess.js](https://github.com/jhlywa/chess.js)

The AI uses the **[Minimax Algorithm](https://en.wikipedia.org/wiki/Minimax)** optimized with **[Alpha-Beta Pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)** for better performance.  

The evaluation function uses **[Piece-Square Tables](https://www.chessprogramming.org/Piece-Square_Tables)** adapted from **Sunfish.py**.  
Instead of recalculating evaluations at every move, the algorithm **updates scores incrementally** for efficiency.  

Additionally, a **global evaluation score** is maintained to display the **advantage bar**.

---

## 👨‍💻 Contributors

| Name           | Contribution                                    |
|---------------|--------------------------------------------------|
| **Zhang Zeyu** | Original author and core implementation          |
| **Shailender** | Fixed check detection logic & improved UI ✨      |

---

## 🕹️ How to Play?

1. Go to **[Play Chess AI](https://shlndra.github.io/chess-ai/ ✅)**.
2. Play as **White** by dragging a piece to your desired position.
3. The AI plays as **Black**.
4. You can customize the AI's **search depth** (difficulty) using the dropdown:
   - Higher depth → smarter AI 🤖 (but slower).
5. To pit **AI vs AI**:
   - Click **Start Game** under *Computer vs Computer*.
   - Stop anytime using **Stop and Reset**.

---

## 📜 License

This project is licensed under the **[MIT License](LICENSE)**.  
You are free to use, modify, and distribute the code.

---

## 🙌 Acknowledgement

> This README now includes credit for **Shailender’s** contributions.

---

## 🛠️ Tech Stack

- **Language:** JavaScript
- **Algorithm:** Minimax + Alpha-Beta Pruning
- **Libraries:** chessboard.js, chess.js

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/shlndra/chess-ai.git

# Go into the project folder
cd chess-ai

# Open index.html in your browser
open index.html
