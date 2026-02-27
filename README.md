
# 💣 Minesweeper Web App

A classic **Minesweeper** game built with **HTML, CSS, and JavaScript**.
Test your logic and luck by uncovering all safe cells without triggering a mine!

---


## 🚀 Features

* 🧩 Classic Minesweeper gameplay
* 🎨 Clean and responsive UI
* ⏱ Timer tracking
* 🚩 Flagging system (right-click to place/remove flags)
* 🔢 Auto-reveal empty cells
* 🏆 Win/Lose detection
* 🔄 Restart button
  

---

## 🛠 Built With

* **HTML5** – Structure
* **CSS3** – Styling & layout
* **Vanilla JavaScript (ES6)** – Game logic & interactivity

---

## 📂 Project Structure

```
minesweeper/
│── index.html

---

## 🧠 How It Works

* The board is generated dynamically using JavaScript.
* Mines are randomly placed across the grid.
* Each cell stores:

  * Whether it contains a mine
  * Number of neighboring mines
  * Revealed/hidden state
  * Flag state
* Clicking a cell:

  * Reveals the cell
  * Ends the game if it's a mine
  * Recursively reveals neighbors if empty
* The game ends when:

  * A mine is clicked ❌
  * All non-mine cells are revealed ✅

---

## 🎯 Game Rules

1. Click a cell to reveal it.
2. Numbers indicate how many mines are adjacent.
3. Right-click to place a flag.
4. Reveal all safe cells to win.
5. Clicking a mine ends the game.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.
Feel free to use and modify it.

---

## 👨‍💻 Author

Michael Nsengiyumva
GitHub: [@mng2650](https://github.com/mng2650)


