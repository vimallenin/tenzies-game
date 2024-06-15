# Tenzies Game

Welcome to the Tenzies game! This is a simple, fun dice game built with React. The goal of the game is to roll until all dice show the same number. You can click on a die to "freeze" it at its current value between rolls.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Components](#components)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## Introduction

Tenzies is a fun and engaging dice game where the objective is to roll the dice until all show the same value. This project demonstrates the use of React for building interactive UIs and managing state.

## Features

- Roll dice until all show the same value
- Click dice to freeze their values
- Confetti animation when the game is won
- Responsive and interactive design

## Technologies Used

- React
- Nanoid for unique ID generation
- React Confetti for the confetti animation

## Setup

To get a local copy up and running, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/tenzies-game.git
    ```

2. **Navigate to the project directory:**
    ```sh
    cd tenzies-game
    ```

3. **Install dependencies:**
    ```sh
    npm install
    ```

4. **Start the development server:**
    ```sh
    npm start
    ```

## Usage

After starting the development server, you can play the game by opening [http://localhost:3000](http://localhost:3000) in your web browser.

1. Click the "Roll" button to roll all the dice.
2. Click on individual dice to freeze their values.
3. Keep rolling until all dice show the same number.
4. When all dice match, the game will display a confetti animation, and you can start a new game by clicking the "New Game" button.

## Components

### `App.js`

This is the main component of the game. It maintains the state of the dice, handles the game logic, and renders the game UI.

Key parts of `App.js`:
- State management for dice and game status.
- Logic to check for a win condition.
- Functions to generate new dice, roll dice, and hold dice.

### `Die.js`

This component represents a single die. It receives props for its value and whether it is held, and applies appropriate styles based on its state.

Key parts of `Die.js`:
- Conditional styling based on the `isHeld` prop.
- Click handler to freeze the die's value.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Contact

Feel free to reach out to me via:

- **LinkedIn:** [Vimal Lenin](https://www.linkedin.com/in/vimal-lenin-18aa46210)
- **GitHub:** [vimallenin](https://github.com/vimallenin)
- **Email:** [vimallenin70@gmail.com](mailto:vimallenin70@gmail.com)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
