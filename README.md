# 🎮 Tic Tac Toe Game

A simple **Tic Tac Toe** game built using **HTML, CSS, and JavaScript**.  
This project demonstrates DOM manipulation, event handling, and basic game logic implementation.

---

## 📂 Project Structure
- **index.html** → Main game layout (grid, buttons, message container).
- **style.css** → Styling for the game board, buttons, and messages.
- **app.js** → Game logic (turns, win detection, reset/new game functionality).

---

## 🚀 Features
- Two‑player game (Player O vs Player X).
- Alternating turns with automatic symbol placement.
- Win detection using predefined patterns (rows, columns, diagonals).
- Displays winner message and disables further moves.
- Reset and New Game buttons to restart the game.
- Responsive design using `vmin` units for scaling.

---

## 🛠️ How It Works
1. Players click on empty boxes to place their symbol (`O` or `X`).
2. The script checks for winning combinations after each move.
3. If a player wins:
   - A congratulatory message is shown.
   - All boxes are disabled.
4. Players can restart using:
   - **Reset Game** → Clears the board but keeps the session.
   - **New Game** → Starts fresh with Player O’s turn.

---

## 🎨 Styling Highlights
- Background color: `#548687`
- Game board with **flexbox layout**.
- Buttons styled with hover/active effects.
- Winner message styled with large font and highlighted color.

---

## 📸 Demo
- Grid of 3x3 boxes.
- Buttons: **Reset Game** & **New Game**.
- Message container shows:  
  *"Congratulations winner is : X/O"*

---

## 📖 Learning Outcomes
- DOM selection (`querySelector`, `querySelectorAll`).
- Event listeners (`addEventListener`).
- Game state management (`turn0`, `enableBoxes`, `disableBoxes`).
- Conditional logic for win detection.
- CSS flexbox and responsive units (`vmin`).

---

## ▶️ How to Run
1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Play Tic Tac Toe with a friend!

 
## 📜 License
This project is open‑source and free to use for learning purposes.
