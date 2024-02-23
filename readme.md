# Tic-Tac-Toe Game

This project is a simple implementation of the classic game Tic-Tac-Toe. It is built using HTML, CSS, and JavaScript.

## Project Structure

The project consists of three main files:

- `index.html`: This is the main HTML file that contains the structure of the game. It includes a game board, a message container to display the winner, and buttons to start a new game or reset the current game.

- `styles.css`: This file contains all the CSS styles used in the project. It is linked in the `index.html` file.

- `app.js`: This is the JavaScript file that contains the game logic. It is linked in the `index.html` file with the `defer` attribute, which means it will only run after the HTML document has been fully loaded.

## How to Run

To run the game, simply open the `index.html` file in your web browser.

## Gameplay

The game board consists of a 3x3 grid. Players take turns clicking on the grid squares to place their mark (either 'X' or 'O'). The first player to get three of their marks in a row (either horizontally, vertically, or diagonally) is the winner. If all squares are filled and no player has won, the game is a draw.

After a game ends, the winner is displayed and players can choose to start a new game or reset the current game.
