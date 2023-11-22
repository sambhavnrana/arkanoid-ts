# Arkanoid TypeScript Game

A classic Arkanoid/Breakout-style game built with TypeScript and Parcel.

## Prerequisites

- [Node.js](https://nodejs.org/) 
- [npm](https://www.npmjs.com/) 

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/sambhavnrana/arkanoid-ts
   cd arkanoid-ts
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

## Development

To start the development server with hot reloading:

```sh
npm start
```

Open [http://localhost:1234](http://localhost:1234) in your browser to play and develop.

## Production Build

To create a production-ready build:

```sh
npm run build
```

The output will be in the `dist/` directory. To serve the production build locally:

```sh
npx serve dist
```

## Project Structure

- `src/` — Source code (TypeScript, HTML, CSS, images)
- `src/sprites/` — Game object classes (Ball, Paddle, Brick)
- `src/view/` — Canvas rendering logic
- `src/index.ts` — Game entry point
- `src/index.html` — Main HTML file
- `src/styles.css` — Game styles
