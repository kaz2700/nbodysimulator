# N-Body Simulator 🌌

A physics-based N-body simulation built with Pygame that simulates gravitational interactions between celestial bodies in real-time.

![Preview](image.jpg)

## Features

- 🚀 Real-time gravitational physics simulation
- 🎮 Interactive controls (zoom, trajectories, info display)  
- ✨ Visual trajectories showing object movement paths
- ⌨️ Intuitive keyboard shortcuts for various display options
- 🌍 Realistic celestial body physics

## Quick Start

### Prerequisites
- Python 3.x
- Pygame

### Installation
```bash
pip install pygame
```

### Usage
```bash
python main.py
```

Make sure you have an `image.jpg` file in the root directory for the background.

## Controls

| Key | Action |
|-----|--------|
| **Mouse Wheel** | Zoom in/out |
| **I** | Toggle info display |
| **Z** | Toggle manual zoom mode |
| **T** | Toggle trajectories |
| **Ctrl+C** | Quit application |

## Project Structure

```
nbodysimulator/
├── main.py          # Main application entry point
├── events.py        # Event handling and user input
├── settings.py      # Application settings and preferences
├── parameters.py    # Simulation parameters
├── objects.py       # Celestial body objects
├── coords_math.py   # Mathematical calculations
├── paint.py         # Rendering and graphics
├── messages.py      # UI messages and text
├── event_booleans.py # Event state management
├── image.jpg        # Background image
└── README.md        # This file
```

## Physics Model

The simulation uses Newton's law of universal gravitation:
```
F = G * (m1 * m2) / r²
```

Where:
- F = gravitational force
- G = gravitational constant
- m1, m2 = masses of the two bodies
- r = distance between centers

## Contributing

Feel free to submit issues and pull requests to improve the simulation!

## License

This project is open source - feel free to use and modify as needed.