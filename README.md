# ModProject1 Version 3 or 4 at this point ><

## Overview

Simple Platformer Game using Vanilla Javascript with HTML Canvas and Phaser 3 Javascript Framework.

## Live Site

You can play the game live at [https://francis-ngo.github.io/](https://francis-ngo.github.io/).

## Technologies Used

- **Phaser ** : Phaser 3 is the core technology powering this project. It's a JavaScript game development framework that simplifies the creation of animations, games, and interactive applications in HTML5 using the HTML canvas element.
- **HTML Canvas**: Used for rendering game graphics and animations.
- **CSS**: Styling and layout of the game elements.
- **JavaScript**: Implemented game logic and user interactions using vanilla JavaScript.
- **VS Code**: The code editor used for development.
- **Live Server**: A local development server extension for VS Code.
- **Node.js**: Used for server-side functionalities (if applicable).
- **GitHub**: Version control and collaboration platform.
- **GitHub Pages**: Used for hosting the live site.

## Approach
After having to restart 3 times with different tutorials and approaches, I decided to just follow a really clear cut tutorial on how to do this. It can be found here: https://mozdevs.github.io/html5-games-workshop/en/guides/platformer/start-here/

## Installation Instructions

To play the game, simply visit the live site at [https://francis-ngo.github.io/](https://francis-ngo.github.io/).

## To run the game locally
1. Download repository
2. Launch a local web server

If you have Node, install `browser-sync`:
```bash
npm -g install browser-sync
```

Inside root directory:
```bash
browser-sync start --server --files="**/*.js"
```

## Challenges

Throughout the development process, several challenges were encountered:

1. **Asset Loading**: Had to restart the project multiple times due to difficulties in loading game assets. Finally found and integrated free assets.

2. **Code Integration**: The games broke each time new code was added, leading to debugging and reworking various components.

3. **Player Input Issues**: Dealing with player input, such as character movement and controls, posed difficulties.

4. **Performance Lag**: The game experienced performance lag during gameplay, impacting the user experience.

5. **Collision Issues**: Implementing accurate collision detection and response proved challenging.

## Unsolved Problems

There are some unresolved issues in the game:

1. Luckily this game works for now. Would love to add more rooms if possible but might be difficult.
