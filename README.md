
# 🪐 Asteroid Game

A simple 2D space shooter game built with Python and Pygame — destroy incoming asteroids before they hit your ship!

> 🚀 Classic arcade-style gameplay with shooting, asteroid splitting, and smooth controls.

---

## 🎮 Gameplay Controls

| Key       | Action                  |
|-----------|--------------------------|
| `W`       | Move forward              |
| `S`       | Move backward             |
| `A` / `D` | Rotate left / right       |
| `SPACE`   | Shoot bullets             |

Avoid collisions and shoot asteroids to survive!

---

## 📹 Gameplay Demo

[▶️ Watch the Demo](#)  
<!-- Replace `#` with your YouTube/GitHub video link or embed a GIF below -->

---

## ✨ Features

- **Player spaceship** that can rotate, move, and shoot
- **Random asteroid generation** from screen edges
- **Asteroids split into smaller ones** upon being shot
- **Collision detection** between player, shots, and asteroids
- Smooth 60 FPS animation loop

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Library**: [Pygame 2.6.1](https://www.pygame.org/news)

---

## 📂 Project Structure
📁 asteroid-game/  
├── asteroid.py # Asteroid behavior and splitting logic  
├── asteroidfield.py # Handles random spawning of asteroids  
├── circleshape.py # Base class for circular game objects  
├── constants.py # Game constants and settings  
├── main.py # Main game loop  
├── player.py # Spaceship movement, rotation, and shooting  
├── shot.py # Bullet class and movement logic  
├── requirements.txt # Pygame dependency

---

## ▶️ How to Run

1. **Install Python** (if not already installed):  
   https://www.python.org/downloads/

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the game**
   ```bash
   python main.py
   ```

---
