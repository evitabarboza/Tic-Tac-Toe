
# 🎮 Tic Tac Toe Game in React

A simple and fun **Tic Tac Toe** game built with **React**, featuring clean UI, dynamic player turns, and win/draw detection.

## 📁 Project Structure

```

Tic-Tac-Toe/
├── src/
│   ├── Components/
│   │   ├── Assets/
│   │   │   ├── circle.png
│   │   │   └── cross.png
│   │   └── TicTacToe/
│   │       ├── TicTacToe.jsx
│   │       └── TicTacToe.css
│   ├── App.js
│   └── index.js
├── public/
│   └── index.html
├── package.json
└── README.md

````


## 🚀 Features

- Classic 2-player Tic Tac Toe game
- React functional components with hooks (`useState`, `useRef`)
- Dynamic win and draw detection
- Reset button to restart the game
- Custom visual icons for player turns


## 🛠️ Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/evitabarboza/Tic-Tac-Toe.git
cd Tic-Tac-Toe
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Development Server

```bash
npm start
```

Then open [http://localhost:3000](http://localhost:3000) to view it in the browser.


## 🧠 Code Overview

### `TicTacToe.jsx`

* Main game logic component
* Uses `useState` to track moves and turns
* Uses `useRef` to directly manipulate DOM elements (boxes and title)
* `toggle()` – handles player moves
* `checkWin()` – checks all winning conditions after each move
* `reset()` – resets the game state and UI

### `TicTacToe.css`

* Styles the board, boxes, title, and reset button
* Simple responsive layout for desktop view


## 📦 Dependencies

* [React](https://reactjs.org/)
* No additional libraries used


## 🖼️ Icons

Images used for players are located in:

```
src/Components/Assets/
├── circle.png
└── cross.png
```

## 📄 License

This project is licensed under the [MIT License](LICENSE).


## 👤 Author

**Evita Barboza**
🔗 [GitHub](https://github.com/evitabarboza)

