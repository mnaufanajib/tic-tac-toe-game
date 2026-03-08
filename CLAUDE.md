# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple web-based Tic Tac Toe game implemented in a single HTML file containing HTML, CSS, and JavaScript. The game features a 3x3 board where players X and O take turns placing their marks, with win detection for all possible winning combinations and draw detection.

## Code Architecture and Structure

### Main Components

1. **HTML Structure**:
   - Game container with title, status display, game board, and reset button
   - Board consists of 9 cells arranged in a grid

2. **CSS Styling**:
   - Responsive layout centered on the page
   - Distinct styling for X (red) and O (blue) players
   - Visual feedback for winning cells (highlighted in green)
   - Hover effects and modern UI design

3. **JavaScript Game Logic**:
   - Game state management (current player, board state, game active status)
   - Event handling for cell clicks and reset button
   - Win detection algorithm using predefined winning patterns
   - Draw detection when board is full
   - Dynamic UI updates (status messages, cell highlighting)

### Key Functions

- `handleCellClick()`: Processes player moves and updates game state
- `checkWin()`: Determines if the current move resulted in a win
- `checkDraw()`: Checks if the game ended in a draw
- `highlightWinningCells()`: Visually highlights the winning combination
- `resetGame()`: Resets the game board and state for a new game

## Common Development Tasks

### Running the Game
Simply open `tic-tac-toe.html` in any web browser to play the game.

### Making Changes
1. Edit the `tic-tac-toe.html` file directly
2. Save changes
3. Refresh the browser to see updates

## Project Files

- `tic-tac-toe.html`: Main game file containing all HTML, CSS, and JavaScript
- `README.md`: Project documentation with features and usage instructions
- `.gitignore`: Specifies files to be ignored by Git