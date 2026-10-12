# 🐍 Wild Snake Adventure

A browser-based snake game built with **HTML, CSS, and JavaScript** for a school science exhibition. It expands the classic Snake concept with selectable animal themes, multiple phases, hazards, optional challenge modifiers, and custom pixel-art graphics.

> **Project type:** Interactive browser game  
> **Built with:** HTML · CSS · JavaScript · Canvas API · Web Audio API  
> **Status:** Exhibition project

## 🎮 Play the game

After publishing with GitHub Pages, add your live URL here:

**Live demo:** Add your GitHub Pages URL here after deployment.

## ✨ Features

- **Three progressive phases:** Easy, Obstacles, and Eagle Hunt.
- **Eight selectable animal themes:** Dog, Cat, Rabbit, Fox, Panda, Tiger, Lion, and Bear.
- **Animal-themed food:** Each animal has its own food item and visual theme.
- **Pixel-art graphics:** Game sprites and environmental objects are drawn with the Canvas API.
- **Hazards:** Rocks, bushes, and an eagle enemy appear as the phases become more challenging.
- **Optional add-ons:** Thunderstorm, Overdrive, Rush Hour, Night Fog, Mirror Mode, Toxic Mushrooms, and Closing Hedge.
- **Keyboard controls:** Arrow keys or WASD.
- **Touch controls:** On-screen directional buttons and touch/swipe support.
- **Sound and music:** Browser-generated sound effects and background music, with a volume control.
- **Progress saving:** Browser local storage remembers unlocked phases and selected settings.
- **Responsive layout:** Designed to adapt to desktop and smaller screens.
- **Pause, retry, and victory screens:** Includes progress and end-of-phase feedback.

## 🕹️ Controls

| Action | Control |
| --- | --- |
| Move | Arrow keys or WASD |
| Pause | Space bar or the in-game pause button |
| Mobile/tablet movement | On-screen arrows or swipe |
| Change sound level | Volume slider |

## 🧠 How it works

- **HTML** structures the menus, game area, buttons, phase cards, and result overlays.
- **CSS** styles the interface, responsive layouts, animations, and visual effects.
- **JavaScript** controls movement, collision checks, phase progression, scoring, hazards, add-ons, and saved progress.
- **Canvas API** draws the game board, pixel-art sprites, snake, food, and visual effects.
- **Web Audio API** generates sound effects and background music in the browser.
- **Local Storage** saves supported progress and preferences on the player's device.

The game runs in the browser and does not require a separate game engine or a server for local play.

## 🚀 Run locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Press **PLAY GAME**, choose a phase and animal, and start playing.

No package installation or build step is required for the current single-file version.

## 🌐 Publish with GitHub Pages

1. Create a **public** repository named `wild-snake-adventure`.
2. Upload `index.html`, `README.md`, `.gitignore`, and `LICENSE` (if using the included license).
3. Open **Settings → Pages** in the repository.
4. Under the build/deployment settings, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site. The published URL will appear in the Pages settings.

If you use a different repository name or account, the final URL will be different.

## 📁 Repository structure

```text
wild-snake-adventure/
├── index.html          # Complete game (HTML, CSS, and JavaScript)
├── README.md           # Project overview and instructions
├── LICENSE             # License information
├── .gitignore          # Common files to exclude from Git
├── docs/
│   └── PROJECT_OVERVIEW.md
└── screenshots/
    └── README.md       # Notes for adding real gameplay screenshots
```

## 🔬 Science exhibition explanation

**Project idea:** Demonstrate how programming concepts can be combined to create an interactive game.

**Concepts demonstrated:**
- User input and event handling
- Coordinates and movement on a grid
- Collision detection and game rules
- Timers and animation updates
- Random placement of game objects
- Drawing graphics with Canvas
- Audio generation with Web Audio
- Saving settings in browser storage
- Interface design and responsive layout

**Suggested live demonstration:**
1. Start the game and explain the controls.
2. Select an animal and show its themed food.
3. Complete the first phase and show how the next phase unlocks.
4. Demonstrate obstacles and the eagle phase.
5. Turn on an optional add-on and explain how it changes gameplay.

## 🛠️ Future improvements

- Separate HTML, CSS, and JavaScript into dedicated files.
- Add automated tests for core game rules.
- Add a settings panel for more accessibility options.
- Improve keyboard and screen-reader accessibility where needed.
- Add a project diagram explaining the game loop and collision logic.
- Add real screenshots and a short gameplay recording.

## 📸 Screenshots

Add your own screenshots to the `screenshots/` folder and embed them here, for example:

```md
![Main menu](screenshots/main-menu.png)
![Gameplay](screenshots/gameplay.png)
![Phase selection](screenshots/phase-selection.png)
```

Only add screenshots that you have actually captured from the game.

## 📄 License

See [`LICENSE`](LICENSE). Keep attribution for any third-party assets you add, and make sure you have the right to publish all included content.

---

Made as a school science exhibition project. 🐍
