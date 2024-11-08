
# 🎮 Tic-Tac-Toe Game

Welcome to the classic **Tic-Tac-Toe** game built in C! This project allows you to play against a **smart computer opponent** that can be adjusted between two levels of difficulty. 🧠💡

## 🎲 Game Modes
- **1. Human Mode (Standard)**: A balanced mode where you have a fair chance of winning.
- **2. God Mode (Impossible)**: The ultimate challenge! The computer uses advanced strategies, making it very difficult to defeat. 😈🕹️

## 💻 How to Play

1. **Launch the game**:
    - Run the executable in your terminal.
2. **Choose the difficulty**:
    - Pick between `1` (Human) or `2` (God).
3. **Make your moves**:
    - As Player X, you’ll go first if chosen randomly.
    - Enter the row and column numbers to place your mark on the board.
4. **Try to win!**:
    - You win by aligning three X's in a row, column, or diagonal.

The computer will try to **block** and **counter** your moves in real-time! 💥💥

## 📊 Score Tracking

After each game, your score will be displayed:
- **Player Wins** 🏆
- **Computer Wins** 🤖
- **Draws** 🤝

The scores will reset once you exit the game.

## ⚙️ Features

- **Dynamic Board**: Updates with each move to reflect the current state of play.
- **Two Levels of Difficulty**:
    - *Human Mode*: Standard gameplay.
    - *God Mode*: Unbeatable strategy using center and corner control.
- **Real-time Feedback**:
    - Displays messages for wins, draws, and whose turn it is.
- **Clear Screen**: Provides a smooth, updated visual after each turn.

## 🛠️ Functions Overview

- **player_move**: Handles player’s moves, validates input, and ensures a smooth experience.
- **computer_move**: AI moves based on difficulty setting. In *God Mode*, the computer prioritizes blocking and winning.
- **check_win & check_draw**: Evaluate the board to determine a winner or if the game has ended in a draw.
- **print_board**: Displays the current state of the game board with score tracking.

## 🎉 Sample Gameplay

- **Win**: Align three X’s or O’s in a row, column, or diagonal.
- **Draw**: When all cells are filled and there’s no winner.

## 📥 Installation and Running the Game

1. **Compile**:
   ```bash
   gcc tic_tac_toe.c -o tic_tac_toe
