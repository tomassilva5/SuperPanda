# Super Panda
Super Panda is a simple 2D platformer game developed with the Phaser 3 framework. Guide the panda through various levels, collect bamboo, avoid hazards, and reach the exit to win. This project was created for a Multimedia Technologies course.

## How to Play

### Objective
Your goal is to guide the panda through each level. To complete a level, you must first collect all the bamboo sticks, then grab the key to unlock the exit door. Be careful to avoid hazards like lava and deep water!

### Controls
-   **Left Arrow:** Move Left
-   **Right Arrow:** Move Right
-   **Up Arrow:** Jump

## Features
-   Two distinct levels with unique challenges and scenery.
-   Classic platformer gameplay with collectible items and hazards.
-   A scoring system based on collected items.
-   Interactive game menus for navigation, level selection, and settings.
-   Adjustable in-game volume.
-   Background music and sound effects for an immersive experience.

## Running the Game

No complex installation is required. The game runs directly in a web browser. For the best experience and to avoid potential browser security issues with loading local files, it is recommended to use a local web server.

### Using VS Code and Live Server
1.  Clone or download this repository and open the `TP2_31373-31425` folder in Visual Studio Code.
2.  If you don't have it, install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension from the VS Code Marketplace.
3.  Right-click on the `index.html` file and select "Open with Live Server", or click the "Go Live" button in the bottom-right corner of the editor.
4.  Your default web browser will open with the game running.

## Project Structure

The repository is organized as follows:

-   `index.html`: The entry point for the game. It loads the Phaser library and all necessary game scripts.
-   `jogo.js`: The main game configuration file. It initializes the Phaser game instance, sets up physics, and registers all the scenes.
-   `Assets/`: This directory contains all static assets used in the game, including images (backgrounds, sprites, UI elements) and audio (music, sound effects).
-   `Cenas/`: This directory holds the JavaScript files for each game scene.
    -   `MainMenuScene.js`: The main title screen with options to play or go to settings.
    -   `LevelMenuScene.js`: The screen for selecting which level to play.
    -   `DefinicoesScene.js`: The settings screen, allowing players to adjust the game volume.
    -   `nivel1.js`: Contains all the game logic, assets, and layout for Level 1.
    -   `nivel2.js`: Contains all the game logic, assets, and layout for Level 2.
