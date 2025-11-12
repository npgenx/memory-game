# React Memory Game

## Overview

This is a simple memory game built via [Vite for React](https://vite.dev/guide/#scaffolding-your-first-vite-project)

## Features

- Shows how to put logic in a custom hook:  [useGameLogic](/src/useGameLogic.js#L3)
- Shows the proper way to use [useCallBack](/src/useGameLogic.js#L20) to `cache` a function in a useEffect 
- show simple component [state management](/src/useGameLogic.js#L4-L9) 

## Getting Started
There is an assumption that you have node and some package manager already installed on you machine. If not, google how to run a nextJS app on my machine.

First, install the app if you have not run it before:
```bash
yarn install
# or
pnpm install
# or
bun install
# or
npm install
```

Once the installation is complated, execute one of the commands below to start the development server:

```bash
yarn dev
# or
pnpm dev
# or
bun dev
# or
npm run dev
```

Open [http://localhost:5173/](http://localhost:5173/) with your browser to see the app.