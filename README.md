# Planetary Simulation with Manim

This repository contains a Python-based 3D planetary simulation using the [Manim](https://www.manim.community/) animation library. The simulation models gravitational interactions between celestial bodies (e.g., the Sun, Earth, and Mars) and animates their motion in a visually engaging 3D environment.

![Planetary Simulation Preview](preview.png)  
*(Insert a GIF or screenshot of your simulation here)*

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Dependencies](#dependencies)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Customization](#customization)
7. [Contributing](#contributing)
8. [License](#license)

---

## Overview

The simulation calculates the gravitational forces between planets using Newton's law of gravitation and updates their positions, velocities, and accelerations iteratively. The resulting motion is animated using Manim's 3D rendering capabilities, providing an interactive and educational visualization of orbital mechanics.

Key features include:
- Realistic physics calculations for gravitational interactions.
- Dynamic camera movement and zoom effects to enhance the visualization.
- Adjustable parameters for time steps, planet properties, and animation speed.

---

## Features

- **Physics-Based Simulation**:
  - Models gravitational forces between multiple celestial bodies.
  - Updates positions, velocities, and accelerations based on physical laws.

- **Dynamic Camera Control**:
  - Smoothly rotates and zooms the camera to provide different perspectives of the simulation.

- **Scalable Design**:
  - Supports adding more planets or celestial bodies with minimal changes to the code.

- **Lighting Effects**:
  - Simulates a light source originating from the Sun, creating realistic shading effects.

---

## Dependencies

To run this simulation, you need the following:

1. **Python** (version 3.8 or higher)
2. **Manim**:
   - Install the latest version of Manim Community Edition:
     ```bash
     pip install manim
     ```
   - Alternatively, follow the installation instructions on the [official Manim documentation](https://docs.manim.community/en/stable/installation.html).
3. **NumPy**:
   - Required for numerical calculations. Install via:
     ```bash
     pip install numpy
     ```

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/planetary-simulation.git
   cd planetary-simulation
   ```
   Install the required dependencies:
   ```bash
   pip install manim numpy
   ```
   Verify that Manim is installed correctly by running:
   ```bash
   manim --help
   ```
