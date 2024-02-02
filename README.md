# MiniChess Project


<img width="652" alt="Screenshot 2024-02-02 at 9 46 12 PM" src="https://github.com/jonathan-4a/minichess/assets/100804161/88be0781-78db-4ff8-acce-ef41c20efeae">


## Overview

The MiniChess Project is a Python-based chess game that utilizes Pygame for its graphical interface and implements the Minimax algorithm with Alpha-Beta pruning for its AI opponent. This project is designed to provide an engaging chess game experience, where a player can compete against an AI that calculates its moves based on game theory optimization techniques.

## Features

- **Graphical User Interface:** Utilizes Pygame for drawing the game board, pieces, and UI elements, making the game visually appealing and interactive.
- **Timer:** Each player has a timer, adding a time-control aspect to the game, similar to competitive chess matches.
- **Minimax with Alpha-Beta Pruning:** The AI opponent uses the Minimax algorithm enhanced with Alpha-Beta pruning to efficiently calculate the best possible move from the current game state.
- **Dynamic Game States:** The game supports detection of checkmate, stalemate, and insufficient material conditions, concluding the game accordingly.

## Installation

1. **Install Python:** Ensure you have Python installed on your system. Python 3.6 or higher is recommended.
2. **Install Pygame:** This project relies on Pygame for rendering the game. Install Pygame using pip:


3. **Clone the Repository:** Download or clone the project repository to your local machine.
4. **Install Dependencies:** Install the required libraries using the provided `requirements.txt` file with pip:



## Running the Game

Navigate to the project's directory in your terminal or command prompt, and run the game using python chess.py:


## Gameplay

- **Playing:** Click on pieces to move them. The game will enforce legal chess moves, including castling, pawn promotion, and en passant.
- **AI Moves:** After making your move, the AI will calculate and make its move. The status bar will show "AI is thinking..." during this process.
- **Winning the Game:** Win by checkmating the AI opponent, or lose if you're checkmated. The game also detects stalemate and insufficient material conditions.
