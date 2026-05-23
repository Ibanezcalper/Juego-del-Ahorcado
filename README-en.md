# Hangman Game

## Project Description
This repository contains an interactive web implementation of the classic "Hangman" game. The main objective of the application is to offer a word guessing pastime (focused on popular names) through an attractive and user-friendly interface.

## Problem Addressed
The project solves the need for a quick and accessible game that can be played directly from any web browser without the need for additional software downloads or installations. It provides an interactive way to improve vocabulary, practice spelling, and offer casual entertainment. Additionally, it serves as a practical example of DOM manipulation and event handling in pure frontend applications.

## Main Features
- **Play Hangman:** Users can try to guess the hidden word by selecting letters through an on-screen keyboard or using their physical keyboard.
- **Add New Words:** Allows users to expand the game's dictionary by adding their own custom words before starting a game.
- **Dynamic Visualization:** The game progressively draws the parts of the hangman with every mistake made, and also keeps track of the incorrect letters entered.
- **Game States:** Automatically detects victory or defeat conditions, displaying the corresponding messages to the user.

## Technologies Used
The project was developed using foundational frontend web development technologies, without relying on external frameworks:
- **HTML5:** For the semantic structure of the application and the layout of elements.
- **CSS3:** For visual styling, responsive design using Flexbox and Grid, and the interactive drawing of the hangman's parts through stylesheets.
- **JavaScript (Vanilla JS):** For the core game logic, capturing keyboard events (physical and virtual), and Document Object Model (DOM) manipulation.

## Usage Instructions
1. **Clone the repository:**
   Download the local files by running the following command in your terminal:
   `git clone https://github.com/Ibanezcalper/Juego-del-Ahorcado.git`
2. **Run the application:**
   No server or complex development environment is required. Simply open the `index.html` file in your preferred web browser (such as Google Chrome, Mozilla Firefox, or Safari).
3. **Gameplay Mechanics:**
   - On the start screen, select "JUGAR" (Play) to begin a game.
   - Press the letters on your physical keyboard or click the virtual keys on the screen to attempt guessing the hidden word.
   - If you wish to add new terms to the game, select "AGREGAR PALABRA" (Add Word) from the main menu.
