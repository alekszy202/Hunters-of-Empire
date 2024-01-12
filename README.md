<h1 align="center"> Hunters of empire - OpenGL Game</h1>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#key-features">Key Features</a> •
  <a href="#technical-specifications">Technical Specifications</a> •
  <a href="#license">License</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  <img src="https://img.shields.io/badge/Author-Degustacja-blue" />
</p>

## Overview
This Space Shooter game, developed in the OpenGL graphics API, is an immersive experience where the player navigates a spaceship through space, fighting enemy spacecraft and avoiding meteorites. The game stands out for its dynamic lighting system, which not only enhances the visual appeal but also plays a crucial role in gameplay mechanics.

### Repository Contents
This repository not only contains the game but also showcases the capabilities of the custom-built mini-engine, demonstrating functionalities such as dynamic lighting, prefab system, rendering techniques, and more, all developed to offer a game engine-like experience without a graphical user interface.

## Screenshots
![Medkit](https://i.ibb.co/5kvtXxR/hunters-of-empire-medkit.png)
*Meteorite field and medical kit.*

![Enemies](https://i.ibb.co/Wzchz62/hunters-of-empire-enemies.png)
*Enemy units approaching the protagonist's ship.*

![Shooting projectile](https://i.ibb.co/RPWtD7C/hunters-of-empire-counterattack.png)
*Player counterattacks with the blue energy cannon.*

![Wireframe](https://i.ibb.co/vqmj52f/hunters-of-empire-wireframe.png)
*A wireframe view of the game.*

## Key Features
### Gameplay
- **Objective**: Defeat all opponents before complete loss of life.
- **Health System**: Colliding with asteroids, enemies and energy bullets results in a loss of health points.
- **Medkit Detection**: Medkits emit a glow, aiding in their detection in the dark space.
- **Weapon System**: Destroy asteroids and enemies using a proton cannon with an 1 second cooldown.

### Graphics and Lighting
- **Dynamic Lighting**: A system that creates stunning cosmic effects and aids in gameplay.
- **Special Effects**: Ship and proton torpedo emit their own distinctive light, contributing to the game's visual appeal.

### User Interface
- **Start Menu**: Simple options to start or exit the game.
- **Control System**: Keyboard controls for ship navigation and actions.
- **Camera**: Mouse-controlled for intuitive rotation and viewing angles.

### Controls
- `W`/`S`: Move the ship forward/backward.
- `A`/`D`: Move the ship left/right.
- `Spacebar`: Move the ship up.
- `Shift`: Move the ship down.
- `F`: Fire proton cannon.
- `Q`/`E`: Toggle triangular object grid display.
- `H`: Toggle ship model visibility.
- `ESC`: Exit the game.

## Technical Specifications
### Libraries
- **FreeType**: For font rendering.
- **glm**: Mathematical operations and entities.
- **glfw3**: Window, context, and event handling.
- **Glad**: OpenGL function loader.
- **Blender**: Object modeling.
- **Gimp**: Texture editing.

### Engine Features
- **Dynamic Light Mechanism**: Spotlight system with variable intensity, radius, and color.
- **Prefab System**: Similar to Unity, allowing object reuse and management.
- **Rendering and Mesh Indexing Systems**: Efficient graphical rendering.
- **Material Creation**: Various shaders and parameters for material customization.
- **Buffer Management**: Automatic handling of graphical buffers.
- **Skybox Creation**: Enhances the environmental setting.
- **Scene Management**: State machine-based system for scene transitions.
- **Static Mathematical and Debugging Libraries**: For efficient calculations and debugging.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
&copy; 2024 Aleksandra Szymczak. All rights reserved.
<p align="left">
  <a href="https://github.com/alekszy202">GitHub</a> •
  <a href="https://www.linkedin.com/in/alekszy202/">LinkedIn</a>
</p>