# 🎮 Overview

Welcome to the **Snake Game** project! In this repository, you'll find the HTML document `index.html`, which serves as a dynamic game selection interface. Players can dive straight into action by choosing between a single-player experience or an engaging multiplayer mode.
👉 **[Play Here](https://tempestaethel.github.io/Snakes/)**

## 🐍 Snake Game Overview

### 🌟 Introduction

This document presents a simple yet captivating **Snake Game** crafted with HTML, CSS, and JavaScript. The game allows players to customize their experience with features like a flexible playing field, adjustable snake speeds, and exciting gameplay elements such as apples and power-ups.

### 🚀 Features

- **Customizable Board Size**: Choose a board size ranging from 10 to 50 squares for endless gameplay variety.
- **Adjustable Snake Speed**: Set the snake’s speed between 1 and 10, allowing for varying difficulty levels.
- **Multiple Apples**: The option to enable multiple apples adds an extra layer of challenge and scoring potential.
- **Power-ups**: Collect power-ups that provide benefits or introduce challenges during gameplay.
- **Responsive Design**: The game interface is designed to be visually appealing and modern, ensuring a smooth user experience.

### 📐 Game Layout

- **Menu**: The game starts with a user-friendly menu where players can set their game parameters:
  - Board Size (input)
  - Snake Speed (input)
  - Options to enable multiple apples and power-ups
  - A **Start Game** button to jump into action.
  - An **Info** button for clear game instructions.

- **Score Display**: Keep track of your score in real-time as you play.
- **Canvas**: The game comes to life on an HTML `<canvas>` element, where the snake, apples, and power-ups are beautifully rendered.

### 🎮 Gameplay Mechanics

- **Snake Movement**: Control your snake using the arrow keys or WASD keys—choose your preferred method.
- **Eating Apples**: When the snake eats an apple, it grows longer, and you rack up points.
- **Power-ups**: Collecting power-ups can speed up or slow down your snake, or even grant bonus points.
- **Game Over**: The game concludes if the snake collides with itself, displaying the final score for bragging rights.

### 🔑 Key JavaScript Functions

- **startGame()**: This function initializes the game settings and starts the game loop.
- **spawnApple()**: Randomly generates apples on the board while ensuring they don't overlap with the snake.
- **spawnPower()**: Creates power-ups in random locations to keep gameplay dynamic.
- **loop()**: The main loop updates the game state, checks for collisions, and redraws the canvas.
- **applyPower()**: Adjusts the snake's speed or score based on the power-ups collected.

### 🎉 Conclusion

This Snake Game combines classic gameplay with modern features to deliver an engaging experience. The flexibility in settings allows for tailored gameplay, while the visual design enhances user interaction.

---

# 🕹️ Multiplayer Snake Game Overview

This project is a complete implementation of a **Multiplayer Snake Game** using HTML, CSS, and JavaScript. Below is a glimpse into its key components.

### 📄 HTML Structure

- **Header**: Displays the game title prominently.
- **Control Panel**: 
  - Input fields for game settings (board size, snake speed, number of apples, and power-up frequency).
  - Buttons to start the game and access game information.
- **Canvas Element**: Where all the game action unfolds.
- **Score Display**: Keeps players updated on their score during gameplay.
- **Game Rules Section**: Initially hidden, this section displays the rules and controls when accessed.

### 🎨 CSS Styling

- **Theme**: A dark, immersive aesthetic with gradients and shadows enhances the gaming experience.
- **Layout**: Centered elements with a modern design provide an enjoyable user interface.
- **Hover Effects**: Buttons and input fields feature smooth transitions, contributing to overall responsiveness.

### 🔍 JavaScript Functionality

- **Game Initialization**: 
  - Reads settings from input fields.
  - Stores them in `localStorage` for a seamless experience.
- **Game Loop**: 
  - Regularly updates the game state (moving snakes, checking collisions, redrawing).
- **Snake Movement**: 
  - Direction control for Player 1 (WASD) and Player 2 (Arrow keys).
- **Apple and Power-Up Management**: 
  - Generates apples and power-ups, tracking consumption and updating scores.
- **Collision Detection**: 
  - Checks for self-collisions, apple collisions, power-up pickups, and snake collisions.
- **Game Over Logic**: 
  - Determines when the game ends and announces the winner.

### 👾 User Interaction

- Players can adjust game settings before launching into action.
- Control your snakes during gameplay for that competitive edge.
- Access game rules easily through a popup for quick reference.

---

Overall, this code creates a functional and engaging multiplayer snake game experience that can be enjoyed directly in your web browser. Jump in and have fun!
