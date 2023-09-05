# Reaction Game

This is a simple Vue.js-based Reaction Game. The goal of the game is to click on the green block as quickly as possible when it appears. Your reaction time will be measured and ranked accordingly.

## Getting Started

1. Clone this repository to your local machine: `git clone git@github.com:mikuskuk/Reaction-Game-Vue.git`
2. Navigate to the project directory: `cd reaction-game`
3. Install the project dependencies using npm or yarn: `npm install` #or `yarn install`
4. Start the development server: `npm run serve` #or `yarn serve`
5. Open your web browser and go to `http://localhost:8080` to play the game.

## How to Play

- Press the "Play" button to start the game.
- A green block will appear on the screen after a random delay.
- Quickly click on the green block when it appears.
- Your reaction time will be displayed, and you'll be given a rank based on your reaction time.

## Project Structure

The project is structured as follows:

`App.vue`: The main Vue component that controls the game flow.
`components/Block.vue`: A component that displays the green block and measures the reaction time.
`components/Results.vue`: A component that displays the player's reaction time and rank.
