<p align="center">
  <img src="images/background_image.png" width="640" alt="PolarisKit Title Screen">
</p>

# ❄️ PolarisKit - A Lightweight, Professional Game Starter Kit for Pygame

**PolarisKit** is a modular, scalable, and beginner-friendly starter kit for building 2D games in Python using Pygame.

It includes built-in scene management, audio control, transitions, save system, and debug overlay, all designed to help you build polished, maintainable games with clean architecture.

---

## 🔍 At a Glance

- Python 3.8+ with Pygame 2.x
- Modular stack-based scene system
- Audio manager with global control
- Seamless fade-in/out transitions via Transition Manager
- Save system with simple JSON persistence
- Debug overlay for live state inspection
- Professional architecture ready for real games

---

## 🚀 Key Features

### Scene Manager

- **SceneManager**: Full stack-based scene switching (`push()`, `pop()`, `replace()`)
- Central manager object that holds all subsystems (`audio`, `save`, `transition`)
- `SceneBase` inheritance ensures clean scene design
- `on_enter()` and `on_exit()` hooks for clean lifecycle transitions

### Transition Manager

- **TransitionManager**: Centralized fade-in and fade-out system
- Overlay transitions run directly within the manager (not as separate scenes)
- Easily extendable for additional transition effects in future versions

### Save Manager

- **SaveManager**: JSON-based save/load/delete support
- Flexible dictionary-based save structure
- Lightweight and easily extendable

### Audio Manager

- **AudioManager**: Unified control of music and sound effects
- Centralized volume control
- Simple API for scene-based sound playback

### Debugging

- Toggleable **Debug Overlay** (TAB)
- Displays FPS and current scene stack state

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

## 👋 Who PolarisKit Is For

- Developers building 2D games with Pygame who want professional architecture
- Students or hobbyists who want clean, extensible templates
- Educators looking for practical code organization for game dev courses
- Game jams or prototypes needing rapid setup with scalable structure

---

## 🕹️ Controls (Default Demo Controls)

- `SPACE`: Start / Confirm
- `ESC`: Pause Menu
- `B`: Resume from Pause
- `Q`: Quit from Pause
- `TAB`: Toggle Debug Overlay

---

## 📦 Requirements

- Python 3.8 or later
- Pygame 2.x

---

## 🌟 Version History

### v2.0 — PolarisKit Core Rewrite (Current)

- Fully modular manager system
- TransitionManager for clean fade transitions
- Unified SceneBase inheritance model
- Scene lifecycle hooks (`on_enter()`, `on_exit()`)
- Central SceneManager holding all managers (`audio`, `save`, `transition`)
- JSON-based SaveManager with delete functionality
- Clean scene switching architecture

### v1.x — Early Versions

- Initial scene stack system
- Debug overlay (TAB)
- Asset loading helpers (`ASSET()`, `IMAGE()`, `SOUND()`, `FONT()`)
- AudioManager introduction
- Early scene argument passing system

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
