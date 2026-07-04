# 🚀 Rocket Boost

A physics-based 3D rocket landing game developed in **Unity** using **C#** as part of the **Complete C# Unity Game Developer 3D** course by GameDev.tv.

The objective of the game is to pilot a rocket through increasingly challenging levels while avoiding obstacles and safely landing on the designated landing pad. The project focuses on Unity physics, particle systems, audio integration, scene management, and creating polished gameplay mechanics.

---

# 📖 Project Overview

Rocket Boost is a 3D arcade-style game where players control a rocket using realistic physics. Instead of directly moving the player, the rocket is propelled using thrust and rotation controls, creating smooth and responsive gameplay.

Players must carefully navigate around obstacles and successfully land on the finish platform without crashing. Each completed level loads the next scene, while collisions with obstacles trigger an explosion and restart the current level.

This project builds upon the Unity fundamentals learned in the previous project (Obstacle Dodge) and introduces several new systems commonly used in game development.

---

# 🎯 Project Objectives

The primary goals of this project were to learn:

* Physics-based player movement
* Rigidbody mechanics
* Applying forces and torque
* Audio integration
* Particle systems
* Scene management
* Collision handling
* Game state management
* Level progression
* Debugging gameplay mechanics
* Writing clean and organized C# code

---

# 🎮 Gameplay

The player controls a rocket attempting to reach the landing platform.

The rocket can:

* Apply upward thrust
* Rotate left
* Rotate right
* Land safely
* Crash into obstacles
* Progress through multiple levels

Each level introduces new layouts and increasingly difficult obstacle placement, encouraging players to improve their control and precision.

---

# ✨ Features

## 🚀 Physics-Based Rocket Controls

* Rigidbody-driven movement
* Realistic acceleration using thrust
* Smooth rotational controls
* Frame-rate independent movement

---

## 💥 Collision Detection

Different collision behaviors:

* Safe landing on Finish Pad
* Crash when hitting obstacles
* Ignore collisions with friendly objects

---

## 🎆 Particle Effects

Visual feedback using Unity Particle Systems:

* Main engine thrust
* Crash explosion
* Successful landing celebration

---

## 🔊 Audio Effects

Integrated audio feedback including:

* Rocket engine sound
* Explosion sound
* Success sound

Audio is synchronized with gameplay events for a more immersive experience.

---

## 🌍 Multiple Levels

* Scene-based level progression
* Automatic loading of the next level
* Restart current level after crashing

---

## 🎯 Landing Mechanics

Players must:

* Control speed
* Control rotation
* Avoid obstacles
* Land gently on the landing platform

Landing too aggressively results in failure.

---

## 🛠️ Debug Features

Development shortcuts include:

* Collision toggle
* Level skipping

Useful for rapid testing during development.

---

# 🛠️ Technologies Used

| Technology      | Purpose              |
| --------------- | -------------------- |
| Unity           | Game Engine          |
| C#              | Programming Language |
| Visual Studio   | IDE                  |
| Unity Physics   | Rigidbody Movement   |
| Particle System | Visual Effects       |
| Audio Source    | Sound Effects        |
| Git             | Version Control      |
| GitHub          | Repository Hosting   |

---

# 📂 Project Structure

```text
Assets
├── Audio
│   ├── Engine Sounds
│   ├── Explosion Sounds
│   └── Success Sounds
│
├── Materials
│
├── Particle Effects
│
├── Prefabs
│
├── Scenes
│   ├── Level 1
│   ├── Level 2
│   ├── Level 3
│   └── ...
│
├── Scripts
│   ├── Movement.cs
│   ├── CollisionHandler.cs
│   └── SceneLoader.cs
│
└── Settings
```

---

# 🎮 Controls

| Key   | Action       |
| ----- | ------------ |
| Space | Apply Thrust |
| A     | Rotate Left  |
| D     | Rotate Right |

---

# 🧠 Unity Concepts Practiced

## Rigidbody Physics

Using Unity's physics engine instead of manually moving objects.

```csharp
rigidbody.AddRelativeForce(Vector3.up * thrust);
```

---

## Player Rotation

Rotating the rocket while maintaining physics interactions.

```csharp
transform.Rotate(Vector3.forward * rotationSpeed);
```

---

## Collision Detection

Using Unity collision callbacks.

```csharp
void OnCollisionEnter(Collision collision)
{
    // Handle collision
}
```

---

## Scene Management

Loading scenes dynamically.

```csharp
SceneManager.LoadScene(nextSceneIndex);
```

---

## Audio System

Playing sounds using AudioSource components.

* Engine sound
* Crash sound
* Success sound

---

## Particle Systems

Triggering particle effects based on gameplay events.

Examples:

* Rocket engine flame
* Explosion
* Landing celebration

---

## Invoke Method

Delaying actions such as restarting or loading the next level.

```csharp
Invoke(nameof(ReloadLevel), delay);
```

---

## Game State Management

Preventing player input after:

* Winning
* Crashing

using boolean state variables.

---

# 📚 Programming Concepts Learned

* Classes and Objects
* Variables
* Methods
* Boolean Logic
* Conditional Statements
* Collision Events
* Rigidbody Physics
* Time-based Programming
* Scene Management
* Object References
* Serialized Fields
* Unity Components

---

# 🚀 Getting Started

## Requirements

* Unity Hub
* Compatible Unity Editor version
* Visual Studio

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Rocket-Boost.git
```

Open the project in Unity.

Load the first scene.

Press **Play**.

---

# 📸 Screenshots

## Main Gameplay

Add gameplay screenshots here.

Example:

```markdown
![Gameplay](Screenshots/gameplay.png)
```

---

## Rocket Landing

```markdown
![Landing](Screenshots/landing.png)
```

---

## Explosion Effect

```markdown
![Explosion](Screenshots/explosion.png)
```

---

# 🔄 Future Improvements

Possible enhancements include:

* Fuel system
* Timer mode
* Checkpoints
* Score system
* Moving obstacles
* Rotating hazards
* Wind mechanics
* Dynamic lighting
* Better explosion effects
* Improved UI
* Pause menu
* Main menu
* Background music
* Achievement system
* Mobile controls
* Controller support
* Save system

---

# 📈 Skills Demonstrated

This project demonstrates practical experience with:

* Unity Game Development
* C#
* Physics Simulation
* Scene Management
* Audio Programming
* Particle Systems
* Collision Detection
* Gameplay Programming
* Level Design
* Git & GitHub

---

# 📚 What I Learned

Through this project, I gained practical experience in building a complete gameplay loop using Unity's physics engine. I learned how to create responsive movement using Rigidbody forces, implement collision-based game logic, manage multiple scenes, integrate particle effects and sound, and organize gameplay scripts into reusable components.

This project strengthened my understanding of Unity's component-based architecture and provided a solid foundation for developing more advanced 3D games.

---

# 👨‍💻 Author

**Abhilash Balabadra**

Computer Science and Engineering Student
SRM Institute of Science and Technology

Aspiring Game Developer passionate about creating games using Unity, Unreal Engine, and C#.

---

# 🙏 Acknowledgements

* GameDev.tv
* Complete C# Unity Game Developer 3D Course
* Unity Technologies
* Open-source Unity Community

---

## ⭐ If you enjoyed this project, consider starring the repository and following my game development journey!

https://github.com/user-attachments/assets/63d37688-ebe2-408f-a629-78523efa75fb
