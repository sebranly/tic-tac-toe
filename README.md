# tic-tac-toe
Tic Tac Toe is a famous 2D game I reproduced in React by following the official tutorial

## Credits

Exceptionally compared to my other contributions on GitHub, for this repository I simply followed a [tutorial](https://reactjs.org/tutorial/tutorial.html). The goal behind that is creating my own commits to see how the app evolved over steps.

## Installation

My development environment was setup by following this [tutorial](https://openclassrooms.com/courses/build-web-apps-with-reactjs/use-create-react-app-to-build-your-react-app).
I installed three main elements on my Windows Machine:
- NodeJS
- Yarn
- create-react-app

I then ran `create-react-app tic-tac-toe` on the Windows Terminal (`C:\Windows\system32\cmd.exe`) to create an example of a basic React project I can start with.
In order to start a local server, I can run `yarn start` and access my React app by navigating to `http://localhost:3000/`

## Structure of the React app

There are three React components being used:
- the `Square` component renders a single `<button>`
- the `Board` renders 9 squares
- the `Game` component renders a board with some placeholders
