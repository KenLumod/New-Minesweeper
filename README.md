# Minesweeper-Inspired Game with Twists

This project is a **Data Structures and Algorithms (DSA)** assignment. The game is inspired by **Minesweeper**, but includes exciting twists like robbery mechanics and coin variants. Developed using **Python**, **Pygame**, and **ImageIO**, it provides a unique spin on the classic game.

---

## Features

### Core Gameplay
1. **Minesweeper Mechanics**:
   - A 6x6 grid where players reveal cells.
   - Cells may contain coins, bombs, or robberies.
2. **Two-Player Mode**:
   - Players alternate turns, competing for the highest score.
3. **Twists**:
   - **Coins**: Reward points (1, 2, or 3) based on type.
   - **Bombs**: End the player's turn.
   - **Robberies**: Deduct points and add an element of risk.

### Enhanced Visuals
- **Dynamic Background**:
  - Animated GIF as the game background for visual appeal.
- **Custom Sprites**:
  - Coins, bombs, and robbery elements are visually distinct.

### Match History
- The game keeps track of the last three matches with timestamps and scores, stored in a file (`match_history.txt`).

### Background Music
- Background music adds an immersive experience.

---

## How to Run

### Prerequisites
1. **Python**: Version 3.8 or newer.
2. **Pygame**: Install using pip:
   ```bash
   pip install pygame
   ```
3. **ImageIO**: Install using pip:
   ```bash
   pip install imageio
   ```

### Execution
1. Clone or download the repository.
2. Place the required image and sound files (e.g., `coin1.png`, `bomb.png`, `giphy.gif`, `forestwalk.mp3`) in the same directory as the script.
3. Run the program:
   ```bash
   python minesweeper_game.py
   ```

---

## Controls
- **Mouse Click**:
  - Left-click to reveal a cell.
- **Game Navigation**:
  - Choose options like Play or Quit on the homepage.

---

## Roadmap

### Current Features
- Two-player gameplay with score tracking.
- Bombs, coins, and robbery mechanics.
- Match history display and persistence.

### Planned Enhancements
- Add AI for single-player mode.
- Implement difficulty levels with larger grids and more twists.
- Improve visual effects and animations.

---

## License

This project is open-source and distributed under the MIT License. Feel free to modify and extend the game for educational or personal use.

