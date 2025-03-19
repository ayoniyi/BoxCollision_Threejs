# 3D Box Collision Physics Simulation

A simple 3D physics simulation built with Three.js that demonstrates box collision and gravity effects in a 3D environment.

## Description

This project features an interactive 3D scene where you can control a cube that interacts with a ground plane using realistic physics. The simulation includes:

- Gravity effects
- Box collision detection
- Shadow rendering
- Interactive camera controls
- Keyboard-based movement controls

## Features

- **Physics Simulation**: Implements basic physics including gravity and collision detection
- **Interactive Controls**: Use keyboard to control the cube's movement
- **3D Environment**: Built with Three.js for smooth 3D rendering
- **Realistic Lighting**: Includes directional and ambient lighting with shadow support
- **Responsive Design**: Adapts to window size changes

## Controls

- **W**: Move forward
- **S**: Move backward
- **A**: Move left
- **D**: Move right
- **Mouse**: Orbit camera around the scene

## Technical Details

The project uses:

- Three.js (v0.150.1) for 3D rendering
- ES Module Shims for module loading
- Custom Box class extending THREE.Mesh with physics properties
- OrbitControls for camera manipulation

## Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. No additional setup required - the project uses CDN-hosted dependencies

## Browser Support

This project requires a modern web browser that supports:

- ES6 Modules
- WebGL
- JavaScript

## License

This project is open source and available under the MIT License.
