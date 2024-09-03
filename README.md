# pairupxo

This project is a classic Tic-Tac-Toe game built using HTML, CSS, and JavaScript. The game offers both single-player and multiplayer modes, providing flexibility and fun for different types of players. The single-player mode includes two difficulty levels: simple and complex.

## Features

- **Game Modes:**
  - **Single Player:** Play against the computer with two difficulty levels:
    - **Simple:** The computer makes basic moves with minimal strategy.
    - **Complex:** The computer uses a more strategic approach to challenge the player.
  - **Multiplayer:** Play against another player on the same device.
  
- **Interactive UI:** A user-friendly interface that responds to player actions with real-time updates and clear notifications.

- **Game Reset:** A button to clear the board and start a new game at any time.

<img src="https://github.com/user-attachments/assets/e07b16c1-8f3e-47e9-bea8-fe7f381cb7a3" alt="tiktactoe" width="400" height="400">


## How to Play

1. **Start the Game:** Open `index.html` in a web browser.
2. **Choose Mode:** 
   - Click on the **Single Player** button to play against the computer, then select the difficulty level (Simple or Complex).
   - Click on the **Multiplayer** button to play against another player on the same device.
3. **Make Moves:** Click on any empty cell to place your mark ('X' or 'O').
4. **Winning or Draw:** The game will notify you when someone wins or if it's a draw. You can restart the game using the reset button.

## Game Logic

- **Board State:** The game maintains the state of the board using a JavaScript array.
- **Winning Combinations:** The game checks for winning conditions using predefined index sets.
- **Computer Moves:** In single-player mode:
  - **Simple Difficulty:** The computer makes random moves.
  - **Complex Difficulty:** The computer uses a more strategic approach, considering winning moves and blocking the player.

## Acknowledgements

- Inspired by the traditional Tic-Tac-Toe game with added features and modes for enhanced gameplay.
