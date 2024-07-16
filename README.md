# rockPaperScissors
This project is a web-based implementation of the classic game Rock, Paper, Scissors. 
The user can play against the computer, and the first to reach 3 points wins the game.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Explanation](#code-explanation)

## Overview
The Rock, Paper, Scissors game allows users to play against the computer. 
The game keeps track of the scores, and the first to reach 3 points is declared the winner. 
The user can reset the game at any time to start over.

## Features
- Play Rock, Paper, Scissors against the computer.
- Track scores for both the player and the computer.
- Display results of each round and declare the winner when one reaches 3 points.
- Reset the game to start over.

## Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites
- A web browser (e.g., Chrome, Firefox, Edge, etc.)

### Installation
1. Clone the repository
2. Navigate to the project directory
3. Open the index.html file in your web browser

## Usage
1. Open the index.html file in your web browser
2. Click the buttons for "Rock," "Paper," or "Scissors" to make your choice
3. The results of each round will be displayed, and the scores will be updated
4. When either the player or the computer reaches 3 points, a message will declare the winner
5. Click the "Reset Game" button to start a new game

## Code Explanation
### JavaScript Functions
- "getRandomComputerResult()": Returns a random choice ("Rock", "Paper", or "Scissors") for the computer
- "hasPlayerWonTheRound(player, computer)": Determines if the player has won the round based on their choice and the computer's choice
- "getRoundResults(userOption)": Calculates the result of a round and updates the scores
- "showResults(userOption)": Displays the results of a round and checks for a winner
- "resetGame()": Resets the game scores and UI elements to start a new game

### Event Listeners
1. Event Listeners for the game buttons:
   - rockBtn
   - paperBtn
   - scissorsBtn
2. "resetGameBtn.addEventListener("click", resetGame)": Add event listener for the reset button
