# Dev Portfolio

A 2D interactive portfolio game built with JavaScript and Kaboom.js, featuring an explorable house environment with various interactive elements and mini-games.

## 🎮 Live Demo

The application is hosted on Vercel: [https://porfolio-blush-delta.vercel.app/]

## 📁 Project Structure

```
├── src/
│   ├── constants.js      # Game constants and dialogue data
│   ├── kaboomCtx.js     # Kaboom.js context configuration
│   ├── main.js          # Main game logic and scene setup
│   └── utils.js         # Utility functions for dialogue and UI
├── public/
│   ├── media/           # Game assets (sprites, music, maps)
│   │   ├── spritesheet.png
│   │   ├── map.png
│   │   ├── map.json
│   │   └── *.mp3 files
│   └── index.html
└── README.md
```

## ✨ Features

**Interactive Environment**
- Explorable 2D house with multiple rooms and objects
- Click-to-move and keyboard controls
- Smooth character animations with directional sprites
- Dynamic camera following

**Educational Content**
- **Geography Quiz**: Test your knowledge of countries, capitals, and landmarks
- **Computer Quiz**: Learn about CPUs, programming languages, and operating systems
- **Globe Quiz**: Explore continents, oceans, and geographical features

**Interactive Elements**
- **Music System**: Change background music at the coffee place
- **Smart Home Facts**: Learn interesting facts about household items
- **Plant Encyclopedia**: Discover information about various plants and flowers
- **General Knowledge**: Fun facts about food, history, and technology

**Technical Features**
- Built with Kaboom.js game engine
- Responsive design with dynamic camera scaling
- Collision detection system
- Audio management with background music
- Interactive dialogue system with branching conversations

## 🎯 Interactive Objects

The game includes various interactive objects throughout the house:

- **Coffee Place**: Music selection interface
- **Computer**: Technology quiz
- **Globe/Map**: Geography challenges  
- **Plants**: Educational content about different species
- **Books**: Literature and gaming facts
- **Kitchen Items**: Food and cooking information
- **Home Appliances**: Historical and technical facts

## 🎵 Audio Features

- Background music with multiple tracks:
  - Hearthome
  - PokeCenter  
  - SandGem
- Dynamic music switching
- Volume controls

## 🕹️ Controls

- **Mouse**: Click to move character to target location
- **Keyboard**: Arrow keys for directional movement
- **Interaction**: Walk into objects to trigger dialogues and quizzes

## 🛠️ Technologies Used

- **Kaboom.js**: 2D game engine
- **JavaScript ES6**: Modern JavaScript features
- **HTML5 Canvas**: Rendering graphics
- **JSON**: Map and configuration data
- **CSS**: Styling and UI elements

## 🚀 Deployment

This project is deployed on Vercel with automatic deployments from the main branch. The build process handles:

- Static asset optimization
- Automatic HTTPS
- Global CDN distribution
- Serverless functions support

## 📱 Responsive Design

The game automatically scales based on screen size and supports both desktop and mobile interactions through touch-to-mouse conversion.

## 🎨 Game Assets

All visual and audio assets are stored in the `public/media` directory:
- Character spritesheets with animation frames
- Tiled map data in JSON format
- Background music tracks in MP3 format
- Environment sprites and textures

## 🔧 Development

To run locally:

1. Clone the repository
2. Serve the files using a local web server
3. Navigate to the main HTML file
4. The game will automatically load and initialize
