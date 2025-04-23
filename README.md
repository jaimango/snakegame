# Snake Game

A simple implementation of the classic Snake game using HTML5 Canvas and JavaScript.

## How to Play

1. Open `index.html` in your web browser
2. Click the "Start Game" button to begin
3. Use the arrow keys to control the snake:
   - ↑ (Up Arrow): Move up
   - ↓ (Down Arrow): Move down
   - ← (Left Arrow): Move left
   - → (Right Arrow): Move right
4. Eat the red apples to grow and increase your score
5. Avoid hitting the walls or the snake's own body
6. The game ends when the snake collides with the wall or itself
7. Compete against the AI snake (red) for food
8. If snakes collide head-to-head, both die
9. If one snake's head hits the other's body, only the colliding snake dies
10. When a snake reaches 10 segments, it splits into two snakes
11. Click "Reset Game" to start a new game

## Features

- Responsive controls
- Score tracking
- Increasing difficulty (snake speeds up every 50 points)
- Pause/Resume functionality
- Visual game over screen
- Death animation when the snake collides with a wall or itself
- Teleportation portals
  - Two portals (blue and purple) allow the snake to teleport from one to the other
  - Portals move to random positions every 10 seconds
  - Portals flash red before moving to warn the player
- AI opponent snake
  - Competes with the player for food
  - Intelligently avoids obstacles and seeks food
  - Red snake with its own death animation
  - Realistic collision detection between snakes
- Snake Splitting
  - When the player's snake reaches 10 segments, it splits in half
  - The tail half becomes a friendly AI snake (light green) that helps collect food
  - The friendly AI shares score with the player
  - Enemy snake (red) also splits when it reaches 10 segments
  - Splits can happen multiple times, creating teams of snakes
- Sound Effects
  - Portal teleportation sound when a snake enters a portal
  - Death sound when any snake dies

## Audio Files

This game uses the following audio files which need to be downloaded and placed in the `assets` folder:

1. `55843__sergenious__port.wav` - Portal teleportation sound
   - Download from [Freesound.org](https://freesound.org/people/Sergenious/sounds/55843/)
   - Place in: `assets/55843__sergenious__port.wav`

2. `642180__n0iz__horror-scary-eyeball-squeeze-squish.wav` - Death sound
   - Download from [Freesound.org](https://freesound.org/people/n0iz/sounds/642180/)
   - Place in: `assets/642180__n0iz__horror-scary-eyeball-squeeze-squish.wav`

If you don't have an `assets` folder, create one in the same directory as the index.html file.

Enjoy playing! 