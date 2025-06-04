<p align="center">
  <img src="images/background_image.png" width="640" alt="PolarisKit Title Screen">
</p>

# 🎮 PolarisKit v1.1

**PolarisKit** is a modular starter kit for building 2D games with Pygame, built by Polaris Studios, the game development branch of SB Studios.

This internal toolkit helps us move from idea to gameplay *fast* with a clean structure, asset management, and scene handling out of the box.

### Features

- Direct **scene management system** (Title, Game, Pause)
- Global **pause system** (ESC key from anywhere)
- Simple asset + sound loader (images, SFX, fonts)
- Scalable, clean **folder structure**
- Built-in **debug overlay** (TAB to toggle)

---

## 💡 Why PolarisKit?

Pygame is a powerful library, but starting from scratch every time can slow development.  
PolarisKit provides a polished foundation so you can focus on what matters: **gameplay**.

---

## 🚀 Upcoming in v2.0

PolarisKit is evolving! Version 2.0 will include:

### Core System Enhancements
- [ ] Refactor `SceneManager` to use **stack-based scene management**
- [ ] Support `push_scene()` and `pop_scene()` methods
- [ ] Maintain active `scene_stack` for layered rendering and logic

### Scene Lifecycle Methods
- [ ] Add `on_enter()` - runs when a scene is pushed
- [ ] Add `on_exit()` - runs when a scene is popped
- [ ] Ensure smooth transitions between scenes

### Global Pause System
- [ ] ESC key pushes the **PauseScene** onto the stack
- [ ] `B` key pops the pause menu and resumes the last scene
- [ ] Optional pause countdown support (e.g., unpause after timer)

### Save / Load System (Simple)
- [ ] Press `SPACE` in MainScene to increase score
- [ ] Press `1` to **save** profile to `saves/1.json`
- [ ] Press `2` to **delete** the save file
- [ ] Basic save file format:
  ```json
  {
    "name": "Player 1",
    "score": 20
  }

---

## 🔒 Code Access

> The codebase is currently **private**.  
> This repository is a **project showcase** highlighting features, screenshots, and development direction.  
> Interested in early access or collaboration?  
> Reach out via [LinkedIn](https://www.linkedin.com/in/marco-a-gonzalez99).

---

## Built By

Marco @ **SB Studios**  
[GitHub](https://github.com/marcogonzalez99) · [LinkedIn](https://www.linkedin.com/in/marco-a-gonzalez99)

---

## Upcoming Projects Using PolarisKit

- **Galactic Tour 64** – Arcade-style racing game  
- **Callisto’s Trial** – Action roguelike 
- More coming soon
