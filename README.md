# Quantum Tunneling & Wavepacket Simulator

A world-class, high-performance web-based physics simulator demonstrating quantum tunneling and wavepacket dynamics.

## Features
- **Rigorous Mathematical Foundation**: Solves the 1-Dimensional Time-Dependent Schrödinger Equation (TDSE).
- **Visscher's Staggered Leap-Frog Method**: Uses an explicit Finite Difference Time Domain (FDTD) scheme to bypass matrix inversion, ensuring real-time 60FPS fluid rendering.
- **Glassmorphism UI**: Clean, premium interface designed for professional academic presentations.
- **Real-Time Interaction**: Modify the potential barrier (height, width) and wavepacket momentum dynamically during simulation.

## Repository Structure
- `/index.html`: Main application entry point.
- `/css/style.css`: Contains all visual styling and UI properties.
- `/js/simulator.js`: The core physics engine and rendering loop.

## How to Run
Simply open `index.html` in any modern web browser. No local server or build process is required.

## Technical Details
- **Spatial Grid**: 500 discrete points.
- **Boundary Conditions**: Infinite Square Well (Dirichlet boundaries: psi = 0 at edges).
- **Stability Condition**: dt < dx^2 / 2 is maintained to prevent numerical blow-up.
