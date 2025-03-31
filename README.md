# Flappy Motu 🎮

A fun and entertaining Flappy Bird clone featuring Motu from Motu Patlu! Navigate through pipes and collect points while Patlu cheers you on.

## Play the Game

To play the game:
1. Host the game using GitHub Pages (recommended)
2. Or simply open `index.html` in your web browser

## Features

- Play as Motu from Motu Patlu
- Progressive difficulty system
- Score tracking
- Patlu appearances on skateboard
- Responsive design
- Sound effects
- Beautiful SVG backgrounds

## How to Play

- Press SPACE or CLICK to make Motu fly
- Navigate through the pipes
- Score points by passing through pipes
- Watch for Patlu's skateboarding appearance when scoring!

## Development

This game is built using:
- HTML5
- CSS3
- Vanilla JavaScript
- Web Audio API for sound effects

## Contributing

Feel free to fork this repository and make improvements!

## 🎲 Difficulty Progression

The game starts easy and gradually becomes more challenging:

- **Initial Settings (Score 0-30)**:
  - Wide pipe gaps (350px)
  - Very slow pipe movement
  - Long intervals between pipes
  - Gentle physics
  - More forgiving collision detection

- **Progressive Difficulty (Score 31-50)**:
  - Gradually decreasing pipe gaps
  - Increasing pipe speed
  - Shorter intervals between pipes

- **Maximum Difficulty (Score 50+)**:
  - Minimum pipe gap (150px)
  - Maximum pipe speed
  - Shortest intervals between pipes

## 🛠️ Technical Details

The game is built using:
- HTML5
- CSS3
- JavaScript (Vanilla)
- SVG graphics for backgrounds
- RequestAnimationFrame for smooth animations
- Web Audio API for synthesized sound effects

## 📦 Project Structure

```
flappy-motu/
├── index.html              # Main game HTML file
├── styles.css             # Game styling and animations
├── script.js             # Game logic and mechanics
├── motu-patlu-images.png  # Main character sprite
└── motu-patalu-ki-image.png  # Popup character sprite
```

## 🎨 Customization

Feel free to modify the game by adjusting these values in `script.js`:
- `GRAVITY`: Controls falling speed (default: 0.3)
- `FLAP_FORCE`: Controls jump height (default: -6)
- `INITIAL_PIPE_SPEED` and `MAX_PIPE_SPEED`: Controls pipe movement speed
- `INITIAL_PIPE_GAP` and `MIN_PIPE_GAP`: Controls gap size between pipes
- `INITIAL_PIPE_SPAWN_INTERVAL` and `MIN_PIPE_SPAWN_INTERVAL`: Controls pipe spawn timing

## 🎮 Game Assets

The game uses two main character sprites:
- `motu-patlu-images.png`: Used for the main playable character (Motu)
- `motu-patalu-ki-image.png`: Used for the popup animation (Patlu)

The background elements (clouds and city skyline) are created using SVG graphics embedded in the CSS for better performance.