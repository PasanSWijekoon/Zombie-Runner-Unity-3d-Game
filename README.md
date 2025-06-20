# Zombie Runner - Unity Project

## Overview

Zombie Runner is a fast-paced, top-down arcade shooter developed in Unity. Players navigate a zombie-infested street, dodging obstacles, destroying enemies, and collecting EXP to level up and build a squad of clones. Designed as a research project, it explores core game development concepts including procedural generation, AI movement, and UI design.

## Table of Contents

*   [Gameplay](#gameplay)
*   [Features](#features)
*   [Technologies Used](#technologies-used)
*   [Controls](#controls)
*   [Setup Instructions](#setup-instructions)
*   [Project Structure](#project-structure)
*   [Credits](#credits)
*   [License](#license)
*   [Contact](#contact)

## Gameplay

In Zombie Runner, you take control of a lone runner battling against endless waves of zombies.

*   **Objective:** Survive as long as possible and achieve a high score.
*   **How to Play:**
    *   **Movement:** Drag your finger (or use the mouse) to move the player character left and right. The character runs forward automatically.
    *   **Shooting:** Weapons fire automatically, targeting enemies in front of the player.
    *   **Power-Ups:** Destroy special obstacles (marked with numbers) to gain powerful effects (e.g., clone players).
    *   **Level Up:** Earn EXP by destroying enemies and regular obstacles to increase the power of your team.
    *   **Game Over:** The game ends when an enemy collides with the player (or any clone).

## Features

*   **Addictive Top-Down Shooter Action:** Fast-paced gameplay with hordes of enemies.
*   **Intuitive Drag Controls:** Easy to pick up and play on mobile devices.
*   **Procedurally Generated Waves:** (If you have implemented that, if not, then remove )Enemies and obstacles spawn in increasing waves.
*   **Dynamic Clone System:** Gather clones powerups to create side by side powerfull shooting
*   **Engaging Progression System:** Earn EXP, level up, and unlock new abilities (if added).
*   **Dynamic formations :** Make the side-by-side the base power and give it new animation like circle, forward and backward formation
*   **Varied Opponents:** Different enemy types that are hard to kill, more powerFull
*   **Powerfull sound and  graphics :** all with the design created in  "zombie style cartoon
*   **Original Soundtracks:** Unique music for each game state to the user.

## Technologies Used

*   **Unity Game Engine:** The primary development platform.
    *   Version: 2021.3.45f1
*   **C# (C-Sharp):** Programming language.
*   **TextMeshPro:** Advanced text rendering for UI.

#### Key Unity Systems Utilized:

*   GameObjects and Components
*   Prefabs
*   Physics Engine (Rigidbodies, Colliders)
*   Unity UI System (Canvas, Panels, Buttons, Sliders, TextMeshProUGUI)
*   Coroutines
*   Audio System
*   Particle Systems

## Controls

*   **Movement:** Drag (Touch) or Mouse (Left/Right)
*   **(Optional) Keyboard Control:** A/D or Left/Right Arrow Keys (if implemented)

## Setup Instructions

1.  Clone this repository: `git clone [Your Repo URL]`
2.  Open the project in Unity Editor (version 2021.3.45f1 or higher).
3.  Ensure you have imported TextMeshPro Essential Resources (Window -> TextMeshPro -> Import TMP Essential Resources).
4.  Run the MainScene!

## Project Structure

```
├── Assets/
│   ├── Audio/              # Music and sound effect assets
│   ├── Models/             # 3D model assets
│   ├── Materials/          # Materials for rendering models
│   ├── Textures/           # Image textures
│   ├── Scenes/
│   │   └── MainScene.unity   # Main gameplay scene
│   ├── Scripts/            # C# scripts
│   │   ├── PlayerEntity.cs
│   │   ├── LeaderMovement.cs
│   │   ├── PlayerManager.cs
│   │   ├── Enemy.cs
│   │   ├── Obstacle.cs
│   │   ├── Projectile.cs
│   │   ├── SpawnManager.cs
│   │   ├── UIManager.cs
│   │   ├── AudioManager.cs
│   │   └── LookAtCamera.cs  
│   ├── Prefabs/            # Prefab assets for reusable objects
│   │   ├── Player/           # Leader player base
│   │   │   ├── PlayerClonePrefab.prefab           # For cloning
│   │   ├── Enemy/
│   │   │   ├── ZombiePrefab.prefab
│   │   ├── Obstacle/
│   │   │   ├── ObstacleBarrelPrefab.prefab 
│   │   ├── UI/              
│   │   │   ├── UIElements
```
