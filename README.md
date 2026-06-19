# Super Panda

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Phaser 3](https://img.shields.io/badge/Phaser%203-Game%20Engine-black?logo=phaser)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)

## Project Overview

Super Panda is a simple 2D platformer game developed with the Phaser 3 framework. Guide the panda through various levels, collect bamboo, avoid hazards, and reach the exit to win. 

This project was created for a **Multimedia Technologies course**.

---

## What's Inside

| Section | Description |
|---|---|
| **Levels** | Two distinct levels with unique challenges and scenery. |
| **Gameplay** | Classic platformer gameplay with collectible items and hazards. |
| **Menus** | Interactive game menus for navigation, level selection, and settings. |
| **Audio** | Background music and sound effects for an immersive experience, with adjustable in-game volume. |
| **Scoring** | A scoring system based on collected items. |

---

## Objective & Controls

- **Objective:** Guide the panda through each level. To complete a level, you must first collect all the bamboo sticks, then grab the key to unlock the exit door. Be careful to avoid hazards like lava and deep water!
- **Movement:** Use the **Left Arrow** to move left and the **Right Arrow** to move right.
- **Action:** Use the **Up Arrow** to jump.

---

## Tech Stack

- **Game Engine:** Phaser 3
- **Languages:** JavaScript, HTML5
- **Development Tools:** Visual Studio Code, Live Server

---

## Repository Structure

| Path | Description |
|---|---|
| **index.html** | The entry point for the game. It loads the Phaser library and all necessary game scripts. |
| **jogo.js** | The main game configuration file. It initializes the Phaser game instance, sets up physics, and registers all the scenes. |
| **Assets/** | This directory contains all static assets used in the game, including images (backgrounds, sprites, UI elements) and audio (music, sound effects). |
| **Cenas/** | This directory holds the JavaScript files for each game scene. |
| **Cenas/MainMenuScene.js**| The main title screen with options to play or go to settings. |
| **Cenas/LevelMenuScene.js**| The screen for selecting which level to play. |
| **Cenas/DefinicoesScene.js**| The settings screen, allowing players to adjust the game volume. |
| **Cenas/nivel1.js** | Contains all the game logic, assets, and layout for Level 1. |
| **Cenas/nivel2.js** | Contains all the game logic, assets, and layout for Level 2. |


---

## How to Run the Project

No complex installation is required. The game runs directly in a web browser. For the best experience and to avoid potential browser security issues with loading local files, it is recommended to use a local web server.

**1. Setup Repository:**
Clone or download this repository and open the `TP2_31373-31425` folder in Visual Studio Code.

**2. Install Extension:**
If you don't have it, install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension from the VS Code Marketplace.

**3. Run the Game:**
Right-click on the `index.html` file and select "Open with Live Server", or click the "Go Live" button in the bottom-right corner of the editor.

**4. Play:**
Your default web browser will open with the game running automatically.
