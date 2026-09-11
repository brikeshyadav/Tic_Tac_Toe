# 🎮 Tic Tac Toe Game

A simple and interactive **Tic Tac Toe** game built using **HTML, CSS, and JavaScript**. This project provides a clean and user-friendly interface where two players can play Tic Tac Toe in the browser.

## 🚀 Live Project

🔗 **GitHub Repository:**
https://github.com/brikeshyadav/Tic_Tac_Toe

---

## 📌 About The Project

**Tic Tac Toe** is a classic two-player game played on a 3×3 grid.

Players take turns placing their symbols:

* **Player 1 → X**
* **Player 2 → O**

The objective is to get **three of your symbols in a row**, either horizontally, vertically, or diagonally.

The game automatically checks the board after every move and determines whether a player has won or the game has ended in a draw.

---

## ✨ Features

* 🎮 Two-player gameplay
* ❌ Player X and ⭕ Player O
* 🏆 Automatic winner detection
* 🤝 Draw detection
* 🔄 Easy game reset/restart
* 🖥️ Simple and responsive user interface
* ⚡ Built with pure JavaScript
* 🎨 Custom styling using CSS
* 🌐 Runs directly in a web browser

---

## 🛠️ Technologies Used

| Technology     | Purpose                                |
| -------------- | -------------------------------------- |
| **HTML5**      | Creates the structure of the game      |
| **CSS3**       | Provides styling and layout            |
| **JavaScript** | Implements game logic and interactions |

---

## 📂 Project Structure

```text
Tic_Tac_Toe/
│
├── index.html
├── style.css
├── Tic_Tac_Toe.js
└── README.md
```

### 📄 File Description

**`index.html`**

Contains the main structure of the Tic Tac Toe game, including the game board, buttons, and other HTML elements.

**`style.css`**

Contains the styling of the game, including the board layout, colors, buttons, spacing, and overall appearance.

**`Tic_Tac_Toe.js`**

Contains the main game logic, including player turns, checking winning combinations, detecting draws, and restarting the game.

---

## 🎯 How To Play

1. Open the game in your browser.
2. Player X starts the game.
3. Player X selects an empty cell.
4. Player O takes the next turn.
5. Players continue taking turns.
6. The first player to get three symbols in a row wins.
7. If all cells are filled without a winner, the game ends in a draw.
8. Use the restart/reset option to play again.

### 🏆 Winning Conditions

A player wins when they get three matching symbols in any of these patterns:

```text
X | X | X
---------
O | O | X
---------
O | X | O
```

Winning can occur:

* Horizontally
* Vertically
* Diagonally

---

## 💻 How To Run The Project

### 1. Clone the Repository

```bash
git clone https://github.com/brikeshyadav/Tic_Tac_Toe.git
```

### 2. Open the Project

```bash
cd Tic_Tac_Toe
```

### 3. Run the Game

Open the following file in your browser:

```text
index.html
```

You can also open the project using **VS Code** and use the **Live Server** extension.

---

## 🧠 Game Logic

The JavaScript program manages the game by:

1. Detecting when a player clicks a cell.
2. Placing the current player's symbol.
3. Switching turns between X and O.
4. Checking all possible winning combinations.
5. Declaring the winner when a winning combination is found.
6. Detecting a draw when all cells are occupied.
7. Allowing the game to be restarted.

---

## 📸 Game Preview

Add a screenshot of your game here:

```markdown
![Tic Tac Toe Game Screenshot](./screenshot.png)
```

---

## 🔮 Future Improvements

Some features that can be added in the future:

* 🤖 Single-player mode with AI
* 🎚️ Different difficulty levels
* 🔊 Sound effects
* 🏆 Scoreboard
* 🌙 Dark mode
* 📱 Improved mobile responsiveness
* 🎨 More animations and visual effects
* 💾 Store player scores using Local Storage

---

## 👨‍💻 Author

**Brikesh Yadav**

GitHub:
https://github.com/brikeshyadav

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is open-source and available for learning and educational purposes.
