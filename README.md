## DEMO LINK
[https://martachobaniuk.github.io/2048_game/]

# 2048 Game
The **2048 Game** is a classic sliding puzzle game implemented in JavaScript. The objective is to combine tiles with the same numbers until you reach the 2048 tile. This project is built with a focus on clean code and maintainability.

## Technologies Used
- **HTML**: Structure of the game interface.
- **CSS (SCSS preprocessor)**: Styling and layout.
- **JavaScript**: Game logic and interactivity.

## Folder Structure

## Folder Structure
- `index.html`: Main HTML file
- `/styles`: Contains the SCSS source files
  - `style.scss`
- `/scripts`: Contains the JavaScript files
  - `game.js`
- `/modules`: Contains the game logic
  - `Game.class.js`
- `/images`: Contains any images used in the game

## Features
- **Clean and Maintainable Code**: Utilizes modular JavaScript to separate concerns.
- **Adaptive Layout**: Ensures usability across various devices.
- **Game Logic**: Implements the classic 2048 mechanics with score tracking and win/lose messages.
- **Keyboard Controls**: Move tiles using arrow keys.

## Commands
| Name    | Command         |
| ------- | --------------- |
| Install | `npm install`   |
| Start   | `npm run start` |
| Build   | `npm run build` |

## Game Logic Overview
- The game initializes with a 4x4 grid filled with zeroes.
- Players can move tiles using arrow keys, merging tiles of the same value.
- The game tracks the score and checks for win/lose conditions.
- New tiles are randomly generated after each valid move.
