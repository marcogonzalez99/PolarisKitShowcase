<p align="center">
  <img src="images/background_image.png" width="640" alt="PolarisKit Title Screen">
</p>

# ❄️ PolarisKit – A Lightweight Game Starter Kit for Pygame

**PolarisKit** is a modular, scalable, and beginner-friendly starter kit for creating 2D games in Python using Pygame.  
It includes built-in scene management, asset handling, audio control, and a global pause/debug system — all designed to help you build polished games faster.

---

## 🔍 At a Glance

- ⌨️ Python + Pygame 2.x
- 🧱 Modular scene system
- 🎧 Built-in audio support
- 🧪 Debug tools for FPS + state
- 🚀 Game-ready architecture in minutes

---

## 🚀 Features

- 🎮 **SceneManager** – Clean scene switching with stack support  
- 🔊 **AudioManager** – Global control for music and SFX across scenes  
- ⏸️ **Pause Menu** – ESC to pause from any scene, with back-to-game or quit options  
- 🎨 **Asset Helpers** – Load images, sounds, and fonts with simple path functions  
- 🧱 **SceneBase** – Shared UI tools like centered text, score rendering, etc.  
- 🧪 **Debug Overlay** – Toggle live FPS, scene info, and more (TAB)  
- 💡 **Modular Folder Structure** – Easy to extend, clean to maintain  

---

## Upcoming Features

## Core Architecture

- [x] Scene stack manager supports push(), pop(), replace()
- [ ] SceneManager supports stack draw behavior (draw entire stack)
- [x] Scene registration system (scene_registry) working

## SceneBase Features

- [x] handle_keydown(event) pattern used consistently
- [ ] input_locked flag implemented in SceneBase
- [ ] compute_fade_alpha() helper in SceneBase
- [ ] transition fade in/out support in SceneBase or SceneManager
- [ ] Scene args supported (SceneBase accepts **kwargs)
- [ ] draw_overlay(screen, alpha) helper available

## SceneManager Features

- [ ] Stack draw behavior implemented
- [ ] Scene args supported (SceneManager can pass args to scenes)
- [ ] Transition fade system supported globally

## Scene Patterns

- [x] All scenes use handle_keydown()
- [x] All scenes use constants for text (TITLE_TEXT, etc.)
- [x] All scenes use helper_font and display credits text
- [ ] Optional: Scenes that need an overlay (Pause, Settings) use draw_overlay()

## Global Features

- [ ] FPS overlay toggle available (SHOW_FPS flag)
- [ ] Simple global config (SHOW_FPS, DEBUG_MODE, etc.)

## Included Standard Scenes

- [x] IntroScene (fade in, text fade in, space to skip)
- [ ] TitleScene (scrollable menu)
- [ ] MainScene (actual game state)
- [x] PauseScene (overlay, back to game, quit)
- [ ] SettingsScene (toggle FPS, Return to Title, other options)

## Code Quality

- [ ] SceneBase remains clean (no scene-specific junk)
- [ ] Scene patterns consistent and reusable
- [ ] Constants used properly
- [ ] No duplication of fade logic across scenes

---

## 📘 Version History

### v2.2 - Event Handler Update
- Removed event handling from the update function
- Added constants for easier management
- Improved Title Screen UI

### v2.1 – AudioManager Update
- Added global `AudioManager` for music and SFX
- Scenes can now control background music and sound effects
- Small bug fixes and formatting improvements

### v2.0 – Modular PolarisKit Core
- Redesigned folder structure for clarity and reusability
- Added `SceneManager`, `SceneFactory`, and `SceneRegistry` system
- Introduced `PauseMenu` scene with built-in controls
- Debug overlay toggle (TAB) with scene name, FPS, and manager state
- Centralized asset loading using `ASSET()`, `IMAGE()`, `SOUND()`, and `FONT()` helpers

### v1.0 – Initial Release
- Basic scene switching and update/draw loop
- Static title screen and placeholder gameplay
- Early asset loader with minimal setup

---

## 🕹️ Controls

- SPACE: Start the game  
- ESC: Pause the game  
- B: Resume from pause  
- Q: Quit from pause  
- TAB: Toggle debug overlay  

---

## 📦 Requirements

- Python 3.8 or later  
- Pygame 2.x  

---

## 💡 Why PolarisKit?

PolarisKit helps you start faster and stay organized when building 2D games with Pygame.  
It's lightweight enough for small arcade projects, but structured enough to support full-scale game systems.

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
- And PolarisKit is just getting started.
