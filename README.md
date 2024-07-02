# The Almost Final Countdown

Welcome to The Almost Final Countdown project! This is a React-based game where players challenge their sense of time by stopping a timer as close to a target time as possible. Below is an overview of the project, including the tech stack, game details, challenges faced, and more.

# Table of Contents

[Tech Stack](#tech-stack)
[About the Game](#about-the-game)
[Challenges Faced](#challenges-faced)
[Project Structure ](#project-structure)

## Tech Stack

- **Frontend**: React
- **Styling**: CSS (with Google Fonts)
- **Build Tool**: Vite
- **Deployment**: Netlify
- **Other Technologies**: React Refs and Portals

## About the Game

The Almost Final Countdown is a timer-based game that tests a player's ability to stop the timer as close to a specified time as possible. The game has a simple user interface with engaging graphics and intuitive controls.

## Key Features

- **Timer Challenges**: Different challenges with varying target times.
- **User Input**: Players can input their estimate and stop the timer.
- **Result Modal**: Displays the result and feedback based on the player's performance.
- **React Refs and Portals**: Used for managing focus, animations, and rendering modals outside the main DOM hierarchy.

## Challenges Faced

- **State Management**: Ensuring that the timer and user inputs are properly managed and updated within the React state.
- **Styling and Responsiveness**: Making sure the game looks good on different devices and screen sizes.
- **User Experience**: Providing clear feedback and an intuitive interface for players.
- **Using Refs and Portals**: Implementing React Refs to manage DOM elements directly and Portals for rendering modals outside the main DOM hierarchy.

## Project Structure

- **index.html**: The main HTML file that sets up the structure of the web page.
- **index.css**: The CSS file that contains styles for the game.
- **main.jsx**: The main React component that initializes the game.
- **Player.jsx**: React component for handling player input and displaying the player's current status.
- **ResultModal.jsx**: React component for displaying the result modal with feedback after each challenge.
- **TimerChallenge.jsx**: React component for managing individual timer challenges.
