# 2048 Game

A browser-based puzzle game built with JavaScript. Slide numbered tiles on a
4 × 4 board, merge matching values, and reach the 2048 tile.

## Live Preview

[Play 2048](https://ievgen-nikiforov.github.io/2048-game/)

## Design Reference

[View the included design reference](src/images/reference.png)

## Technologies Used

- **HTML5** — page structure and game board.
- **SCSS** — board styling, tile colors, and controls.
- **JavaScript (ES6+)** — game logic, keyboard input, and score updates.
- **Parcel** — development server and production bundling.
- **ESLint, Stylelint, and linthtml** — JavaScript, stylesheet, and HTML linting.

## Getting Started

### Prerequisites

Install Git and Node.js with npm. The project's CI configuration uses Node.js 20.

### Run locally

1. Clone the repository and enter the project directory:

   ```bash
   git clone https://github.com/ievgen-nikiforov/2048-game.git
   cd 2048-game
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the local URL printed in the terminal.

### Build and lint

```bash
npm run build
npm run lint
```

The production build is generated in `dist/`.

## Features

- A 4 × 4 board with arrow-key controls.
- Matching tiles merge into a tile with twice their value.
- Each successful move adds a random tile with a value of 2 or 4.
- The score increases by the value of each merged tile.
- Win and loss messages appear when you reach 2048 or run out of moves.
- A button starts a fresh game and resets the board and score.

### How to play

Click **Start**, then use **←**, **↑**, **→**, and **↓** to slide the tiles.
Combine equal values to reach **2048**. The game ends when you win or no moves
remain. Click **Restart** after a win or loss to play again.
