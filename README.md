# Chrome Dino Game Clone

## Description
This is a **Chrome Dino Game** clone recreated using **p5.js** for graphics and **JavaScript** for the game logic. The player controls a dinosaur (Dino) to jump over cacti and aims to keep the game running for as long as possible.

### Features:
- Control the dinosaur to jump over cacti.
- Continuous scrolling background effect to simulate the game progressing.
- Displays a "Game Over" message when the dinosaur collides with a cactus, and prompts the player to press **Enter** to restart the game.
- Manages the score using **D3.js**.

## Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ngvanloi/dino.git
   cd dino
   ```

2. **Install the Required Libraries**
   - If you want to use D3.js and other libraries, make sure you have them installed via `npm` or simply include them using CDN links.

   **Example using CDN:**
   ```html
   <script src="https://d3js.org/d3.v7.min.js"></script>
   ```

3. **Open the File Using Live Server in Visual Studio Code**
   - Open the `index.html` file in **Visual Studio Code**.
   - Install the **Live Server** extension in Visual Studio Code (if you haven't already).
   - Right-click on the `index.html` file and select **Open with Live Server** to view the game in your browser.

## How to Play
- **Press the "Space" key** to make the dinosaur jump.
- **Avoid the cacti** and try to achieve the highest score possible.
- **Press the "Enter" key** to restart the game after it's over.

## Folder Structure
```
/dino-game
    ├── index.html      # Main HTML file for the game
    ├── style.css       # CSS styles for the game
    ├── script.js       # JavaScript logic for the game
    ├── images/         # Images (background, dinosaur, cactus, etc.)
    └── README.md       # This README file
```

## Acknowledgements
Thank you for trying out this game! I hope you enjoy playing it. If you have any questions or contributions, feel free to open an issue or submit a pull request.