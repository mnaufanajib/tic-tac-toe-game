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

## Development Workflow

### Git Practices

As you work on this project, it's essential to maintain proper version control:

1. **Commit Frequently**: Make commits as you complete logical units of work
2. **Write Descriptive Commit Messages**: Each commit message should clearly describe what changes were made and why
3. **Push to GitHub Regularly**: Push your commits to the GitHub repository to ensure work is backed up and accessible

### Commit Message Guidelines

- Use clear, concise messages in present tense (e.g., "Add feature" not "Added feature")
- Start with a capital letter
- Keep the first line under 72 characters if possible
- Use additional lines for detailed explanations when needed

Example good commit messages:
- "Add player turn indicator to status display"
- "Fix bug preventing diagonal win detection"
- "Improve responsive design for mobile devices"

### Git Commands

- `git add .` - Stage all changes
- `git commit -m "Your descriptive message"` - Commit changes
- `git push origin main` - Push changes to GitHub
- `git pull origin main` - Pull latest changes from GitHub

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