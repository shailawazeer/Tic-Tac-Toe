# 🎮 Tic-Tac-Toe Game

A classic Tic-Tac-Toe game built with vanilla JavaScript, HTML, and CSS. Simple, clean, and fun to play!

## 🚀 Features

- **Two-player gameplay** - Enter your names and battle it out
- **Smart win detection** - Automatically detects wins and ties
- **Clean UI** - Responsive design with smooth interactions
- **Modal dialogs** - Player name input and winner announcements
- **Game reset** - Start fresh anytime

## 🎯 How to Play

1. Open `index.html` in your browser
2. Enter both player names in the dialog
3. Player 1 (X) goes first, then Player 2 (O)
4. Click any empty cell to place your mark
5. First to get 3 in a row wins!
6. Game automatically detects wins, ties, and prevents invalid moves

## 🛠️ What I Learned

This project helped me practice key JavaScript concepts:

- **Array methods**: `some()` for win detection, `forEach()` for UI updates
- **Event handling**: Click listeners and form submissions
- **DOM manipulation**: Dynamic class additions/removals
- **Module pattern**: Separating game logic, display, and flow control
- **Data attributes**: Using `dataset` to store cell positions

## 📁 Project Structure

```
├── tictactoe.html          # Game layout and structure
├── style.css           # Styling and responsive design
└── tictactoe.js           # Game logic and interactions
    ├── Gameboard()     # Core game state and rules
    ├── DisplayController() # UI updates and visual feedback
    └── GameFlow()      # Turn management and game flow
```

## 🎨 Architecture Highlights

The code follows a modular approach:

- **Gameboard**: Handles game state, moves, and win conditions
- **DisplayController**: Manages visual updates and CSS classes  
- **GameFlow**: Controls turns, player management, and game lifecycle

This separation makes the code maintainable and easy to extend!

## 🔧 Technical Details

- **Win Detection**: Uses `some()` method to efficiently check all 8 winning patterns
- **Turn Management**: Boolean flag to alternate between players
- **State Management**: Separate game logic from visual representation
- **Event Delegation**: Single click listener handles all cell interactions

## 🚀 Quick Start

1. Clone this repo
2. Open `tictactoe.html` in any modern browser
3. Start playing!

No build process, no dependencies - just pure vanilla JavaScript fun! 🎉

---

*Built as a learning project to practice JavaScript fundamentals and DOM manipulation.*
