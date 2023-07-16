# Calculator App

This is a simple calculator application built using React.js. The calculator allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (÷)
- Clearing the calculation (AC)
- Deleting the last entered digit (DEL)
- Evaluating the expression (=)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/imohamnur/calculator-app.git

2. Install the dependencies:

   ```bash
   cd calculator-app
   npm install

3. Run the application:

   ```bash
   npm start

## How It Works

The calculator app uses a `useReducer` hook from React to manage the state of the calculator. The state includes the current operand, previous operand, and the selected operation.

The `reducer` function handles various actions to update the state based on user interactions. These actions include adding a digit, choosing an operation, clearing the calculation, deleting a digit, and evaluating the expression.

The `evaluate` function performs the actual calculation based on the selected operation and the operands. It returns the computed value as a string.

The app's UI consists of a grid layout with buttons for digits (0-9), decimal point (.), and operation buttons (+, -, *, ÷). The output section displays the previous and current operands along with the selected operation.

## Acknowledgements

- This project was inspired by this youtube video: https://www.youtube.com/watch?v=DgRrrOt0Vr8&list=PLZlA0Gpn_vH_NT5zPVp18nGe_W9LqBDQK&index=37
- [React](https://reactjs.org) - A JavaScript library for building user interfaces.

## Author

Isaac Mohammed Nur (https://github.com/imohamnur)
