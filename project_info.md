# Physics Test Project

This project is a physics simulation test environment built with Astro.

## Technical Stack
- Node.js version: 22
- Framework: Astro
- Language: TypeScript/JavaScript

## Overview
This project aims to explore and implement various physics simulations through an interactive web interface.

## Project Structure
The project is organized as follows:
- `src/`: Source code directory
  - `pages/`: Astro page components
  - `layouts/`: Layout components
  - `components/`: Reusable Astro components
- Documentation and resources

## Getting Started
To run the physics simulations:
1. Ensure Node.js v22 is installed
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the development server:
   ```bash
   npm run dev
   ```
4. Open your browser and navigate to the local development server

## Components

### FaradayGenerator3D (`src/components/FaradayGenerator3D.astro`)
A 3D simulation of Faraday's Law of Electromagnetic Induction using Three.js.

#### Features
- Interactive 3D visualization of a rotating wheel with alternating magnets
- Real-time EMF, current, and power calculations
- Adjustable parameters:
  - Rotation speed (RPM)
  - Magnet strength (Tesla)
  - Number of coil turns
- Visual elements:
  - Horizontal rotating wheel with 8 alternating N/S pole magnets
  - Copper coil with LED indicators
  - Single central support pole
  - Interactive camera controls

#### Technical Implementation
- Uses Three.js for 3D rendering
- Real-time EMF calculation using Faraday's Law: EMF = -N * d(phi)/dt
- Physically accurate lighting and materials
- Responsive design with proper scaling
- OrbitControls for camera manipulation

#### Physics Simulation
- Implements Faraday's Law of Electromagnetic Induction
- Calculates induced EMF based on:
  - Magnetic field strength
  - Angular velocity of the wheel
  - Number of coil turns
  - Effective area of the coil
- Visual feedback through LED brightness changes

#### User Interface
- Real-time display of:
  - Induced EMF (Volts)
  - Current (milliamps)
  - Power (milliwatts)
- Slider controls for adjusting simulation parameters
- Smooth animation and transitions

## Contributing
Feel free to contribute by:
- Adding new physics simulations
- Improving existing implementations
- Fixing bugs
- Enhancing documentation
