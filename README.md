<p align="center">
  <img src="images/background_image.png" width="640" alt="PolarisKit Title Screen">
</p>

# ❄️ PolarisKit - A Lightweight, Professional Game Starter Kit for Pygame

**PolarisKit** is a clean, scalable, and beginner-friendly 2D game starter kit built in Python using Pygame.  
It provides a polished foundation with modular systems, making it ideal for both rapid prototyping and complete games.

---

 [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J41IBU2Y)

---

## 🔍 At a Glance

- Python 3.8+ with Pygame 2.x  
- Clean, modular architecture with centralized managers  
- Stack-based scene manager with lifecycle hooks  
- Transition system with smooth fade effects  
- JSON-based save system with easy toggling  
- Audio system for music/SFX playback  
- Toggleable debug overlay for live scene/fps data

---

## 🚀 Key Features

### Scene Management

- `SceneManager` supports full stack control: `push()`, `pop()`, `replace()`
- Holds shared managers: `audio`, `save`, `transition`, `screen`, `clock`
- All scenes inherit from `SceneBase` for consistent API
- Hooks: `on_enter()` and `on_exit()` for clean lifecycle control

### Transitions

- `TransitionManager` enables fade-in and fade-out overlays
- Non-intrusive: overlays sit on top of the current scene
- Customizable speed and opacity
- Delivers seamless scene transitions for a more polished user experience

### Save System

- `SaveManager` stores data as plain JSON
- Includes `load()`, `save(data)`, `delete()`, and `exists()` methods
- Automatically creates file on first access
- Assumes well-structured behavior from developers for flexibility

### Audio System

- `AudioManager` plays music and SFX from `/assets/sounds/`
- `play_music()`, `play_sfx()`, and volume toggles
- Scene-aware audio control

### Debugging

- **Debug Overlay** (toggle with `TAB`)
- Displays current scene and FPS info
- Built-in to `SceneBase`, no setup required

---

## 🌐 Architecture Overview

### Managers

- SceneManager (Core runtime stack)
- AudioManager (Music/SFX control)
- SaveManager (Persistent save system)
- TransitionManager (Fade transitions)

### Folder Structure

- `polariskit/`
  - `main.py`
  - `managers/`
    - `scene_manager.py`
    - `audio_manager.py`
    - `save_manager.py`
    - `transition_manager.py`
  - `scene_engine/`
    - `scene_base.py`
    - `scene_loader.py`
    - `scene_registry.py`
    - `scene_factory.py`
  - `scenes/`
    - (your game scenes)
  - `settings/`
    - `config.py`
    - `paths.py`
  - `assets/`
    - `fonts/`
    - `images/`
    - `sounds/`
  - `data/`
    - `saves/`
  - `README.md`

---

## 🕹️ Demo Controls

| Key         | Action                  |
|-------------|-------------------------|
| `SPACE`     | Start / Interact        |
| `ESC`       | Pause Menu              |
| `Q`         | Quit (from Pause)       |
| `B`         | Resume Game (from Pause)|
| `S`         | Toggle save value       |
| `D`         | Delete save data        |
| `TAB`       | Toggle Debug Overlay    |

---

## 🌟 Version History

### ✅ v3.0 — Complete PolarisKit Cleanup (2025-08-02)

- Full project-wide refactor for professionalism and consistency
- Added docstrings to every manager, config file, and asset loader
- All `SceneBase` children now follow offset constants and consistent layout structure
- Save toggles and transitions implemented in demo scenes
- Assumes responsible dev usage (minimal error handling, favoring clarity and control)
- File structure and naming polished across all modules

### 🔄 v2.0 — PolarisKit Core Rewrite

- Lifecycle hooks (`on_enter()` / `on_exit()`)
- Unified scene stack manager with shared managers
- JSON-based save/load/delete system
- AudioManager and TransitionManager introduced
- First stable modular release

### 🧪 v1.x — Experimental Stack Prototype

- Initial proof of concept for stack-based scene switching
- Basic AudioManager and DebugOverlay
- No scene registry or auto-loading

---

## 👋 Who PolarisKit Is For

- Developers building 2D games with Pygame who want professional architecture
- Students or hobbyists who want clean, extensible templates
- Educators looking for practical code organization for game dev courses
- Game jams or prototypes needing rapid setup with scalable structure

---

## 📦 Requirements

- Python 3.8 or later
- Pygame 2.x

---

## 🔒 Code Access

> This repository is currently **private**.
>
> This showcase demonstrates the system architecture, features, and future direction of PolarisKit.
>
> Interested in early access or collaboration?  
> Reach out on [LinkedIn](https://www.linkedin.com/in/marco-a-gonzalez99).

---


## 🔧 Built By

Marco @ **SB Studios**  
[GitHub](https://github.com/marcogonzalez99) · [LinkedIn](https://www.linkedin.com/in/marco-a-gonzalez99)
