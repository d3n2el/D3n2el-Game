
# Game of Life

A 2D platformer game that tells an autobiographical story through different life stages and experiences.

## What This Project Does

Game of Life is a narrative-driven platformer where players control a pixel character through various levels representing different stages of life. The game combines storytelling with classic platformer mechanics, featuring:

- **Story-driven gameplay**: Each level represents a different life stage (childhood, adolescence, etc.)
- **Cultural elements**: Levels include various cultural references with flags, food, and landmarks
- **Progressive difficulty**: Multiple levels with increasing complexity and different objectives
- **Visual storytelling**: Uses pixel art and symbolic imagery to convey life experiences

### Game Features

- **Player Movement**: Smooth character control with left/right movement and jumping
- **Physics System**: Realistic gravity and collision detection
- **Multiple Levels**: Several distinct levels with unique themes and layouts
- **Interactive Elements**: Ground tiles, brick tiles, and various collectible items
- **Level Progression**: Flag-based level completion system
- **Loading System**: Smooth asset loading with animated loading screen
- **Transition Screens**: Story elements between levels with continuation choices

### Technical Features

- **HTML5 Canvas**: Smooth 2D graphics rendering
- **Modular JavaScript**: Object-oriented programming with separate classes
- **Asset Management**: Efficient image loading and management system
- **Responsive Design**: Adapts to different screen sizes
- **Custom Fonts**: Uses Google Fonts (Italiana) for enhanced typography

## How to Run

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Running the Game

1. **Download or Clone** this repository to your local machine
2. **Navigate** to the project folder
3. **Open** `index.html` in your web browser
4. **Click "Yes"** when prompted "Do you want to play the game?"
5. **Wait** for the loading screen to complete
6. **Start playing** using the controls below

### Game Controls

- **Move Left**: Left Arrow Key or 'A'
- **Move Right**: Right Arrow Key or 'D'  
- **Jump**: Spacebar
- **Navigate Menus**: Use the on-screen options during transition screens

### Alternative Access

You can also directly open `game.html` in your browser to skip the main menu and go straight to the game.

## Screenshots

### Main Menu Interface
![Main Menu](https://hc-cdn.hel1.your-objectstorage.com/s/v3/87038e14767e163c9d258b2be00be4178c343c7a_capture.png)

### Gameplay in Action
![Gameplay](https://hc-cdn.hel1.your-objectstorage.com/s/v3/55659a39838527f934ee576e3e55ad6563f27e6c_cap2.png)

### Level Environment with Cultural Elements
![Level Transition](https://hc-cdn.hel1.your-objectstorage.com/s/v3/063ebae229001ad144a314f2edaac9ca675ea984_cap3.png)

### Level Transition Screen
![Level Environment](https://hc-cdn.hel1.your-objectstorage.com/s/v3/e109006d846ba404f13e6d0d769f0d5566f5ec32_cap4.png)

---

### Technologies Used

- **HTML5** - Game structure and canvas element
- **CSS3** - Styling and loading screen animations  
- **JavaScript (ES6+)** - Game logic, physics, and interactivity
- **HTML5 Canvas API** - 2D graphics rendering
- **Google Fonts** - Typography (Italiana font family)

### File Structure

- `game.html` - Main game page
- `game.js` - Core game logic and level data
- `allClasses.js` - Game object classes (Player, UI, Background, ImageLoader)
- `InputHandler.js` - Keyboard input management
- `game.css` - Game styling and animations
- `images/` - All game assets and sprites
