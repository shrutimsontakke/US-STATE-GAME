<h1>US-STATES-GAME</h1>

This project is a fun and interactive game to learn and test your knowledge of the U.S. states. It uses the `turtle` graphics module in Python to display a map of the U.S., prompting the user to name each state. If a guessed state is correct, the name is displayed on the map at the state's location. The goal is to correctly identify all 50 states!!

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Play](#how-to-play)


## Project Overview
The U.S. States Game uses a blank map of the United States and prompts the player to guess the names of the states. Correct guesses display the state name on the map, while incorrect guesses prompt the user to try again. Once the player chooses to exit the game, a CSV file (`states_to_learn.csv`) is generated with the states that were not correctly guessed.

## Features
- Interactive map with `turtle` graphics
- User prompt to guess the names of U.S. states
- Dynamic text display of correctly guessed states on the map
- CSV file generation of states to learn after the game ends

## Technologies Used
- Python
  - turtle
  - pandas

## Installation
To get started, clone this repository and install the necessary dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shrutimsontakke/U.S.-States-Game.git
   cd U.S.-States-Game
   ```

2. **Install dependencies:**  
   The game requires Python and the `pandas` library. You can install `pandas` via pip:
   ```bash
   pip install pandas
   ```

3. **Add the U.S. States CSV File:**
   Make sure to have the `50_states.csv` file in the same directory. This file should contain columns for each state's name and its x/y coordinates on the map.

4. **Run the Game:**
   Start the game by running the script:
   ```bash
   python us_states_game.py
   ```

## How to Play
1. The game displays a blank map of the U.S. on the screen.
2. You will be prompted to enter the name of a U.S. state.
3. If your guess is correct, the state’s name will appear on the map at the appropriate location.
4. Continue guessing until you have identified all 50 states or choose to exit.
5. If you exit early, a CSV file named `states_to_learn.csv` will be created, listing the states you did not guess.

<div align="center">
Happy gaming, and enjoy learning about U.S. states!!</div>
