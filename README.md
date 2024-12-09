# Block Drop Game

A 3D block drop game built using Three.js and JavaScript. In this game, the player drops blocks onto a moving platform, trying to match the block's position with the platform. The objective is to keep stacking blocks without missing. Each successful drop increases the score, and if a drop fails, the game ends.

## Features
- 3D graphics rendered with Three.js.
- Interactive gameplay: Click or tap to drop blocks.
- Dynamic camera that adjusts to the block's position.
- Score tracking and game-over screen.
- Responsive to window resizing.

## Installation

### Prerequisites
To run this project locally, you'll need:
- A modern web browser (e.g., Chrome, Firefox, Safari).
- An internet connection (for downloading external libraries).

### Steps to Run Locally

1. **Clone or Download the Repository**  
   Clone the repository to your local machine or download the files.

   ```bash
   git clone https://github.com/your-username/block-drop-game.git
   ```

2. **Open the Project**  
   Navigate to the folder containing the project files and open the `index.html` file in your browser.

3. **Enjoy the Game**  
   The game should load in your browser. Use a mouse click or tap to start dropping blocks.

## How to Play
1. Click or tap on the game screen to drop a block.
2. The goal is to match the position of the falling block with the previously placed block. 
3. If the overlap is successful, the game continues with a new block. Each successful drop increases your score.
4. If the drop doesn't match, the game ends and shows your final score.
5. The camera view adjusts as the blocks stack higher.

## Controls
- **Click** or **Tap**: Drop the block onto the moving platform.
  
## Game Over
When the game ends, a "Game Over" screen will appear, showing your final score. You can restart the game by clicking the "Restart" button.

## Technologies Used
- **Three.js**: For rendering 3D graphics and animations.
- **JavaScript (ES6)**: For game logic and interactivity.
- **HTML/CSS**: For structuring and styling the game interface.

## Credits
- **Three.js** - A JavaScript 3D library that makes WebGL easier to work with. [Visit Three.js](https://threejs.org/)
- **TweenLite** - A lightweight animation library used for smooth transitions. [Visit TweenLite](https://greensock.com/tweenlite/)

## License
This project is open source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.
