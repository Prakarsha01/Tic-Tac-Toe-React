# Tic-Tac-Toe Game

This project is a simple implementation of the classic game Tic-Tac-Toe using React. It allows two players to take turns marking spaces in a 3x3 grid, aiming to get three of their symbols in a row horizontally, vertically, or diagonally. The game also keeps track of the player's moves and displays the winner or declares a draw when the game is over.

## Features

- **Player Names:** Players can customize their names by clicking the "Edit" button next to their symbol.
- **Game Board:** The game board displays the current state of the game, allowing players to select empty squares to make their moves.
- **Log:** The log section keeps track of each player's move, displaying the player's name and the coordinates of the selected square.
- **Game Over:** When a player wins or the game ends in a draw, a "Game Over" message is displayed along with the option to start a new game.

## How to Play

1. Enter the desired names for Player 1 (X) and Player 2 (O) by clicking the "Edit" button next to their symbols.
2. Click on an empty square on the game board to make a move.
3. Players take turns making moves until one player wins or the game ends in a draw.
4. If the game ends, click the "Rematch!" button to start a new game.

## File Structure

- **App.jsx:** The main component that orchestrates the game logic, including managing player turns, determining the winner, and handling restarts.
- **GameBoard.jsx:** Component responsible for rendering the game board and handling square selections.
- **Player.jsx:** Component for displaying player information and allowing players to edit their names.
- **GameOver.jsx:** Component to display the end game message and option to restart.
- **Log.jsx:** Component for displaying a log of player moves.
- **WINNING_COMBINATIONS.js:** Constant array containing all possible winning combinations in Tic-Tac-Toe.
- **index.css:** Contains styles for the entire application, including fonts, colors, and animations.
- **Index.jsx:** Entry point of the application where the `App` component is rendered into the DOM.


## Technologies Used

- React: A JavaScript library for building user interfaces.
- useState Hook: Used for managing state within functional components.
- JSX: A syntax extension for JavaScript used with React to describe the UI components.
- CSS: Stylesheets to enhance the visual appearance of the game.

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the development server using `npm run dev`.
5. Open your web browser and go to  the provided localhost address to view the game.

## Acknowledgments

This project is part of the ["React - The Complete Guide 2024 (incl. React Router & Redux)"](https://www.udemy.com/course/react-the-complete-guide-incl-redux/) course on Udemy, which provides comprehensive training on React and its ecosystem. Special thanks to the course instructors for the guidance and inspiration.
