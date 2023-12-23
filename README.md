# 2048 game

My version of the game 2048. The game is implemented for both the desktop version and mobile devices. The playing field can be moved using the arrow keys on the keyboard or by swiping on the screen.

# [Live Demo](https://vlkzmn.github.io/2048_game/)

# Technologies used

- HTML5
- CSS3
- Sass (SCSS)
- JavaScript

# Game logic

- The game field is 4 x 4 (16 cells), but it can be easily changed to any size in code
- Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
- The game starts with 2 cells filled with 2 or 4
- The game can be started by clicking the `Start` button
- The player can move cells with keyboard arrows or swipe in screen
- All the numbers are moved in the selected direction until all empty cells are filled in
   - 2 equal cells are merged into a doubled number
   - The merged cell can’t be merged twice during one move
- The move is possible if at least one cell is changed after the move
- After move 2 or 4 appears in a random empty cell. 4 probability is 10%
- When `2048` value is displayed in any cell, win message will be shown.
- The `game over` message will be shown if there are no more available moves.
- Score is increased by the sum of all merged cells.
- The game can be restarted by clicking the `Restart` button.

# How to run the project locally

- Fork and clone this repository
- Run `npm install` in your terminal
- Run `npm start` in your terminal to start the project locally

# Reflections

The main goal of this project was to practice JavaScript and DOM manipulations and combine JavaScript with HTML and CSS.

The main task was to implement game logic and the ability to switch with a swipe. I had to think through all possible scenarios and ways to implement them.

Eventually I practiced in building more complex logic using knowledge I have gained so far until this point.

### This project is inspired by original [2048 game](https://play2048.co/)
