# Tic Tac Toe Android App

The Tic Tac Toe Android App is a straightforward and engaging two-player game designed for Android devices. This repository contains the source code and resources for the app, allowing you to understand its structure, features, and usage. This README serves as a comprehensive guide to help you explore and utilize the app effectively.

# Introduction

The Tic Tac Toe Android App is a digital rendition of the timeless Tic Tac Toe game. It provides an interactive and enjoyable way for two players to compete against each other on a 3x3 grid. The app leverages modern Android development practices and the Jetpack Compose UI toolkit to deliver a user-friendly and visually appealing experience.

# Features

1) Two-Player Gameplay

Players take turns to mark empty spaces on the grid with their designated symbols (X or O). The app ensures a fair competition, simulating the classic pen-and-paper gameplay while providing real-time feedback.

2) Real-time Result Display

The app immediately updates players with the outcome of each move. If a player achieves a winning combination or the game ends in a draw, a result dialog is presented, offering instant acknowledgment of the game's status.

3) Player Name Customization

Before starting a game, players have the opportunity to personalize their experience by entering their names. This adds a layer of familiarity and engagement to the matches.

4) Responsive UI

The app employs Jetpack Compose, a modern UI toolkit, to create a responsive and visually pleasing user interface. Whether on phones or tablets, the UI dynamically adapts to various screen sizes and orientations.

5) App Structure

The app is organized into three main components:

6) MainActivity

This component is the core of the app, managing the gameplay logic, user interactions, and result determination. It handles the grid display, player turns, and triggers the result dialog when a match is concluded.

7) AddPlayers

The AddPlayers activity enables users to input the names of both players before starting a game. These names are then used throughout the gameplay to enhance the personalization of the experience.

8) ResultDialog

The ResultDialog is a custom dialog class responsible for displaying the outcome of a game. It dynamically informs players whether a player has won or the game has ended in a draw. The "Start Again" button allows users to restart the game without re-entering player names.

# Usage

1) Getting Started

   1) Clone this repository to your local machine.
   2) Open the project in Android Studio.
   3) Build and run the app on an emulator or physical device.

2) Gameplay

   1) Upon launching the app, enter the names of Player One and Player Two.
   2) Tap the "Start Game" button to commence the game.
   3) Players alternate turns by tapping on empty grid spaces to place their symbols (X or O).
   4) When a player achieves a winning combination or the grid is filled without a winner, a result dialog appears.
   5) Use the "Start Again" button in the result dialog to reset the game while retaining the player names.
