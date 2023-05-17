## Scoreboard App

This is a simple React application that allows you to keep track of players and their scores in a scoreboard.

### Installation

To run this application locally, follow these steps:

1. Clone the repository or download the source code.
2. Make sure you have [Node.js](https://nodejs.org) installed.
3. Open a terminal and navigate to the project directory.
4. Run the following command to install the required dependencies:

   ```shell
   npm install
   ```

5. After the installation is complete, run the following command to start the development server:

   ```shell
   npm start
   ```

6. Open your web browser and visit `http://localhost:3000` to see the application running.

### Usage

The Scoreboard app displays a list of players with their scores. You can perform the following actions:

- Increment a player's score by clicking the "+" button next to their score.
- Decrement a player's score by clicking the "-" button next to their score.
- Remove a player from the scoreboard by clicking the "X" button next to their name.

### Components

The application is composed of the following React components:

#### Header

The `Header` component displays the title of the scoreboard and the total number of players.

#### Counter

The `Counter` component represents a player's score counter. It provides buttons to increment and decrement the score. The current score is stored in the component's state.

#### Player

The `Player` component displays a player's name, along with a `Counter` component for managing their score. It also provides a button to remove the player from the scoreboard.

#### App

The `App` component is the main component that manages the state of the scoreboard. It contains the `Header` component and a list of `Player` components. The `App` component handles the logic for removing players from the scoreboard.

