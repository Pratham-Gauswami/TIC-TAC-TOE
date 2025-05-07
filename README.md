# TIC-TAC-TOE Game

Welcome to TIC-TAC-TOE, a classic two-player game implemented in C!

## Introduction

TIC-TAC-TOE is a simple yet engaging game where two players take turns marking spaces in a 3x3 grid, aiming to create a row, column, or diagonal of their chosen symbol (usually X or O). The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is declared the winner.

## How to Play

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your-username/tic-tac-toe.git
   ```

2. Navigate to the project directory:
   ```
   cd tic-tac-toe
   ```

3. Compile the source code:
   ```
   gcc -o tic-tac-toe main.c
   ```

4. Run the executable:
   ```
   ./tic-tac-toe
   ```

5. Follow the on-screen instructions to play the game:
   - Enter the coordinates to place your mark (e.g., A1, B2, C3).
   - Alternate turns with your opponent until one player wins or the game ends in a draw.

## Features

- Simple command-line interface for easy gameplay.
- Supports two-player mode, allowing players to compete against each other locally.
- Checks for winning conditions after each move and announces the winner.
- Includes error handling to prevent invalid moves and ensure smooth gameplay.
