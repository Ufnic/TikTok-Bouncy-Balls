# TikTok-Bouncy-Balls

A browser-based HTML5 Canvas simulation featuring a ball bouncing inside a circular boundary with gravity, trails, and an escape exit.

## Features

- **Circular Boundary**: Ball bounces inside a circular arena with a visible stroke
- **Gravity Physics**: Realistic gravity pulls the ball downward
- **Bounce Trails**: Each bounce leaves a glowing trail that fades over time
- **Exit Gap**: A small opening in the circle allows the ball to escape
- **Ball Deletion**: When the ball exits through the gap, it is removed from the simulation
- **Smooth Animation**: Uses `requestAnimationFrame` for optimal performance
- **Clean Code**: Well-structured with comprehensive comments

## How to Use

1. Open `index.html` in a modern web browser
2. Click the "Start" button to begin the simulation
3. Watch as the ball bounces with gravity and leaves trails!
4. The ball will eventually escape through the exit gap
5. Click "Reset" to restart the simulation

## Technical Details

- **Canvas Size**: 800x800 pixels
- **Circle Radius**: 350 pixels
- **Gravity**: 0.5 pixels/frame² acceleration
- **Damping**: 98% energy retention on bounce
- **Ball Radius**: 15 pixels (constant)
- **Exit Gap**: Small opening at the top of the circle
- **Trail Duration**: 2 seconds with fade effect

## Browser Compatibility

Works in all modern browsers that support:
- HTML5 Canvas
- ES6 Classes
- requestAnimationFrame

## Demo

Simply open the `index.html` file in your browser - no build process or dependencies required!