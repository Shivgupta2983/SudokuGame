# Java Sudoku Game 🧩

## Preview
![Sudoku Game Preview](https://github.com/username/java-sudoku-game/raw/main/screenshots/game-preview.png)

## Overview
A polished Java implementation of the classic Sudoku puzzle game using Swing GUI. Challenge yourself with different difficulty levels and enjoy a clean, intuitive interface! 🎮

## Features
* **Multiple Difficulty Levels:** Choose between Easy, Medium, and Hard modes to match your skill level! 🔢
* **Real-time Feedback:** Instant color-coded feedback shows correct and incorrect entries! ✅❌
* **Auto-generation:** Every puzzle is uniquely generated with guaranteed solutions! 🎲
* **Visual Subgrids:** Clear 3×3 subgrid visualization for easier solving! 📊
* **Solution Checking:** Validate your progress at any time! 🔍
* **Solve Button:** Stuck? Reveal the solution with one click! 💡

## Technologies Used
* Java ☕
* Swing GUI 🖼️
* Backtracking Algorithm 🧠

## Game Logic
The game implements several key algorithms:
* **Puzzle Generation:** Creates valid, solvable Sudoku boards using backtracking techniques! 🧩
* **Difficulty Control:** Strategically reveals a specific number of cells based on difficulty level! 🎚️
* **Input Validation:** Real-time validation ensures only legal moves are permitted! ✔️
* **Solution Verification:** Checks your answers against the generated solution! 🔍

## Code Structure
* **SudokuGame.java:** Main class containing the game logic, UI, and puzzle generation algorithm! 📜
* **Puzzle Generation:** Uses randomized diagonal subgrids and backtracking for complete solutions! 🎲
* **UI Components:** Clean Swing interface with styled text fields and control buttons! 🎨

## How to Play
1. Launch the application 🚀
2. Select your preferred difficulty level 🎚️
3. Click "New Game" to start a fresh puzzle 🆕
4. Enter numbers (1-9) in the empty cells ⌨️
   - Green background means correct entry ✅
   - Red background means incorrect entry ❌
   - Gray background indicates fixed/given cells (cannot be modified) 🔒
5. Click "Check Solution" to validate your progress 🔍
6. If stuck, click "Solve" to reveal the complete solution 💡

## Future Enhancements
* Timer functionality to track solving speed! ⏱️
* Hint system for when you're stuck! 💭
* Puzzle saving and loading! 💾
* High score tracking! 🏆
* Additional grid sizes (6×6, 12×12)! 📏

## Game Rules
Standard Sudoku rules apply:
* Fill the 9×9 grid with digits 1-9 🔢
* Each row must contain digits 1-9 without repetition ↔️
* Each column must contain digits 1-9 without repetition ↕️
* Each 3×3 subgrid must contain digits 1-9 without repetition 📦

## Credits
* Developed by: Shiv Gupta 👨‍💻
* Inspired by classic Sudoku puzzles 💡

## License
[MIT License](LICENSE) 📝
