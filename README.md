# MPCR – Multiplayer Car Racing Game

## Project Overview

MPCR (Multiplayer Car Racing) is a browser-based multiplayer car racing game developed using HTML, CSS and JavaScript. It allows multiple players to participate in a racing game and tracks their progress using Firebase Realtime Database.

## Features

- Multiplayer racing experience supporting up to four players.
- Player registration using their names.
- Real-time player information synchronization.
- Car movement and distance tracking.
- Interactive racing environment.
- Game reset functionality.

## Technologies Used

- HTML – Structure of the application.
- CSS – Styling and layout.
- JavaScript – Game logic and functionality.
- p5.js – Graphics and game canvas.
- p5.play.js – Sprite and game object management.
- Firebase Realtime Database – Multiplayer data synchronization.

## Project Structure

```text
MPCR/
│
├── images/
│   ├── track.jpg
│   ├── car1.png
│   ├── car2.png
│   ├── car3.png
│   ├── car4.png
│   └── ground.png
│
├── js/
│   ├── Form.js
│   ├── Game.js
│   └── Player.js
│
├── index.html
├── sketch.js
├── style.css
├── p5.play.js
└── README.md
```

## How to Run the Project

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` using a local development server, such as VS Code Live Server.
4. Enter a player name.
5. Click the Play button to participate in the game.
6. Use the UP arrow key to move your car forward.

A working Firebase configuration and appropriate database security rules are required for multiplayer functionality.

## Game Workflow

1. Players enter their names.
2. Player information is stored in Firebase.
3. The game synchronizes player data.
4. Cars are displayed on the racing track.
5. Players move forward and their distances are updated.
6. The game tracks the progress of participating players.

## Future Improvements

- Add more racing tracks and car options.
- Improve graphics and animations.
- Introduce a leaderboard system.
- Add sound effects and background music.
- Improve the user interface and responsiveness.

## Contribution

Contributions and suggestions for improving the project are welcome.