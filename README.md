# Rōnin Dan Ranking Board
A lightweight, portable, and offline-first dan ranking board designed for local gaming scenes. Rōnin allows you to track player progress, character ranks, and competitive points with a retro arcade aesthetic, all from a single HTML file that runs directly in your browser.

The app saves all data to your browser's local storage, ensuring your rankings are preserved between sessions. You can also import and export your data as a `.csv` file, making it easy to manage multiple ranking boards for different games or communities.

## Table of Contents
1. [Key Features](#key-features)
2. [Installation](#installation)
3. [How to Use](#how-to-use)
4. [Contributing](#contributing)
5. [License](#license)
6. [Credits](#credits)    
7. [Support and Contact](#support-and-contact)

## Key Features
- **Player & Character Tracking:** Add multiple players and track an unlimited number of characters for each.
- **1-to-10 Dan Ranking System:** A classic ranking structure from Shodan (1 Dan) to Judan (10 Dan), perfect for fighting games and other competitive scenes.
- **Point-Based Promotions:** Players rank up after earning +3 points and de-rank at -3 points, with automatic point resets on rank change.
- **Dynamic Sorting:** Players are automatically sorted by points. Players with identical points can be manually reordered.
- **Data Persistence:** All data is automatically saved to the browser's local storage.
- **CSV Import & Export:** Easily back up your board or manage multiple communities by exporting and importing your data.
- **Retro Arcade UI:** A stylish, pixel-font interface with a dark mode theme, smooth animations, and celebratory confetti effects.
- **Fully Portable:** Runs entirely from a single `.html` file. No server or internet connection required after the initial load.

## Installation
As a self-contained application, Rōnin requires no complex installation or dependencies.

**For End-Users:**
1. Download the `index.html` file.
2. Double-click the file to open it in any modern web browser (like Chrome, Firefox, or Edge).    
3. That's it! You can start adding players.

## How to Use

### Adding a Player/Character
1. Enter a unique **Gamer Tag** and the **Character** name in the "Add Player / Character" form.
2. Click **"Add Entry"**.    
3. New players are automatically placed in **10 Dan** with 0 points. If the Gamer Tag already exists, the new character will be added to that player's profile.

### Managing Ranks and Points
- Use the **`+`** and **`-`** buttons next to a character to add or subtract points.
- The system automatically handles rank-ups and de-ranks based on the point thresholds.    
- A celebratory confetti effect will trigger upon a rank-up.

### Reordering Players
- Use the **`↑`** and **`↓`** arrows to change a character's position.
- You can only reorder characters who have the **same number of points** within the same dan rank.

### Importing and Exporting Data
- **Export:** Click the **"Export CSV"** button to save a `index.csv` file of your current board.    
- **Import:** Click the **"Import CSV"** button and select a valid `.csv` file. **Warning:** This will overwrite all data currently on the board.

## Contributing
Contributions are welcome! If you have suggestions for improvements or encounter a bug, please feel free to open an issue on the project's GitHub repository.

When reporting a bug, please include:
- A clear and descriptive title.
- Steps to reproduce the bug.
- What you expected to happen vs. what actually happened.    
- Your browser and operating system.

## License
This project is distributed under the GNU GPL-2.0 License. See the `LICENSE` file for more information.

## Credits
- **Concept & Development:** [Aaron Calzado](https://www.aaroncalzado.com "null")
- **AI-Assisted Development:** [Google Gemini](https://gemini.google.com/ "null")

## Support and Contact
For support, questions, or to report an issue, please open an issue in the GitHub repository for this project.
