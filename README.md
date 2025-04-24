# Two-Player Connect Four Game (Bash)

## Description

This project implements a simple two-player Connect Four game using Bash scripts. Players take turns dropping their tokens into one of seven columns, aiming to connect four in a row horizontally, vertically, or diagonally. The game runs in a terminal session and uses inter-process signaling.

## Requirements

- Unix-like operating system
- Bash shell (version 4 or higher)

## Setup

1. Clone or download the repository containing the two scripts:
    - `player1` (first player)
    - `player2` (second player)

2. Make both scripts executable:
   ```bash
   chmod u+x player1 player2

3. Ensure both scripts reside in the same directory.

## Running the Game

1. In one terminal window, start the first player:
   ```bash
   ./player1

2. In a second terminal window, start the second player:
    ```bash
   ./player2

3. Follow on-screen prompts to begin and play:

    - In the terminal of the first player, select "y".
    - Enter a column number (1–7) to drop your token.
    - Type "exit" at any prompt to surrender or leave the game.

## How to Play
- Players alternate turns, dropping one token per turn.
- Tokens occupy the lowest available cell in the chosen column.
- The first player uses “X” tokens; the second player uses “O” tokens.
- The goal is to align four of your tokens in a row:
    - Horizontally
    - Vertically
    - Diagonally
- The game ends when one player connects four, the grid fills (draw), or a player exits.

# Good luck in the game!
