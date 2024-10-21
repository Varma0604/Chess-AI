# Chess AI Game

This project is a simple **Chess AI Game** built using HTML, CSS, JavaScript, Chessboard.js, and Chess.js. The game allows a player to play chess against an AI that makes random moves. The player can also adjust the AI's difficulty level.

## Features

- **Interactive Chessboard**: Allows the player to drag and drop pieces to make their moves.
- **AI Opponent**: The AI opponent makes random legal moves.
- **Move History**: Displays the history of moves made by both the player and the AI.
- **AI Difficulty Levels**: The player can select between Easy, Medium, and Hard difficulty levels.
- **Status Updates**: Displays game status, including checkmate and draw notifications.
- **Restart Button**: Allows players to reset the game and start a new one.

## Technologies Used

- **HTML5**: For structuring the page.
- **CSS3**: For layout and styling.
- **JavaScript**: For handling the game logic and interactions.
- **[Chessboard.js](https://chessboardjs.com/)**: For rendering the chessboard.
- **[Chess.js](https://github.com/jhlywa/chess.js/)**: For handling the game rules and move validation.
- **jQuery**: Used for DOM manipulation and event handling.

## Installation & Setup

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/chess-ai-game.git
    ```

2. Navigate to the project folder and open the `index.html` file in your browser:
    ```bash
    open index.html
    ```

No additional setup is required.

## How to Play

1. Start the game by clicking the **"Start New Game"** button.
2. Drag and drop the chess pieces to make your moves. The AI will automatically respond with its own moves.
3. Select the AI difficulty level from the dropdown (Easy, Medium, Hard) to challenge yourself.
4. The **Move History** section on the right will display all the moves made during the game.
5. The **Status** below the board will display game results, such as **Checkmate** or **Draw**.
6. Reset the game anytime by clicking the **"Start New Game"** button.

## Customization

- **AI Difficulty Levels**: While the AI currently makes random moves, you can improve the AI behavior by integrating more advanced decision-making algorithms or libraries.
- **Move Timing**: The AI currently waits 250ms before making its move. You can adjust this timing by modifying the `window.setTimeout(makeRandomMove, 250);` line in the JavaScript code.

## Project Structure

```bash
Chess AI Game/
├── index.html         # Main HTML file
├── README.md          # Project documentation
└── chessboard-1.0.0.min.css   # CSS for the chessboard (included via CDN)
└── chessboard-1.0.0.min.js    # JavaScript for the chessboard (included via CDN)
└── chess.min.js       # JavaScript for chess rules and move validation (included via CDN)
