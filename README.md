# TikTok-Bouncy-Balls

A browser-based HTML5 Canvas simulation featuring bouncing balls with physics, growth, spawning, and sound effects.

## Features

- **Realistic Ball Physics**: Balls bounce inside a rectangular canvas with proper collision detection
- **Edge Collision**: When a ball hits an edge, its velocity is reversed in the appropriate direction
- **Ball Growth**: Each collision grows the ball's radius by 10%
- **Ball Spawning**: Each collision spawns a new ball with slightly different velocity (±20% variation)
- **Sound Effects**: Short synthesized "boop" sounds play on each collision using Web Audio API
- **Smooth Animation**: Uses `requestAnimationFrame` for optimal performance
- **Clean Code**: Well-structured with comprehensive comments

## How to Use

1. Open `index.html` in a modern web browser
2. Click the "Start" button to begin the simulation
3. Watch as balls bounce, grow, and multiply!
4. Click "Reset" to restart with a single ball

## Technical Details

- **Canvas Size**: 800x600 pixels
- **Maximum Balls**: Limited to 100 to prevent performance issues
- **Ball Growth Rate**: 10% radius increase per collision
- **Velocity Variation**: ±20% for spawned balls
- **Sound**: Synthesized using Web Audio API with pitch based on ball size

## Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas
- ES6 Classes
- Web Audio API
- requestAnimationFrame

## Demo

Simply open the `index.html` file in your browser - no build process or dependencies required!