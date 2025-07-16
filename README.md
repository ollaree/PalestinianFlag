# 3D Palestinian Flag

An interactive 3D representation of the Palestinian flag built with Three.js.

## Features

- Interactive 3D flag with drag to rotate and scroll to zoom
- Accurate flag colors: black, white, green stripes with red triangle
- Smooth controls with damping and realistic lighting
- Responsive design that adapts to window resizing

## Setup

1. Save the HTML file locally
2. Open in a web browser
3. Drag to rotate, scroll to zoom

## Technical Details

- **Built with**: Three.js r160, OrbitControls, WebGL
- **Requirements**: Modern browser with ES6 modules and WebGL support
- **Structure**: 3 horizontal stripes (2 units each) with left-side triangle
- **Anti-z-fighting**: Red triangle positioned slightly forward to prevent flickering

## Customization

Modify these variables in the code:
- `flagWidth` and `stripeHeight` for dimensions
- Material hex values for colors
- Light properties for different lighting effects
