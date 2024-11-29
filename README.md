# Faraday Generator Physics Simulation

This project simulates a Faraday generator using Three.js for 3D visualization. The simulation demonstrates electromagnetic induction through a rotating magnetic wheel and copper coil setup.

## Components and Structure

### Physical Structure
1. Base Plate
   - Horizontal flat plate serving as the foundation
   - Supports all other components

2. Copper Coil
   - Spherical coil design
   - Mounted horizontally on the base plate
   - Connected to LED indicators via copper wires

3. Support Structure
   - Mounted on sides of the coil
   - Contains bearings for wheel rotation
   - Provides stable support for the rotating wheel

4. Magnetic Wheel
   - Mounted above the coil
   - Contains alternating magnets (N-S poles)
   - Rotates to induce current in the coil

5. LED Indicators
   - Two LED lights connected to the coil
   - Brightness varies with induced current
   - Demonstrates AC current generation

### Visualization Features
- Realistic copper coil with spherical winding
- Magnetic field visualization using particles
- Real-time EMF, current, and power readings
- Interactive controls for:
  - Rotation speed (RPM)
  - Magnet strength (Tesla)
  - Number of coil turns

## Technical Implementation
- Three.js for 3D rendering
- Physics-based calculations for electromagnetic induction
- Real-time updates of electrical parameters
- Particle system for magnetic field visualization

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
