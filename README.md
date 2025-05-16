# 🎯 First-Person Shooter Prototype — Unreal Engine 5

> Development: Blueprint-only | Engine: Unreal Engine 5.5  
> Project Type: Single-player FPS with advanced shooting mechanics, custom animation, and modular HUD

---

📖 Read this in other languages: [🇷🇺 Русский](README_ru.md)
## 📽️ Demo & Build

- ▶️ [Gameplay Video (YouTube)]()
- 📦 [Download Build (Google Drive)]()

---

## 🚀 Key Features

### 🎮 Shooting & Interaction
- **Dead Zone Aiming** — weapon is not locked to the center of the screen, aiming is done intuitively via muzzle position
- **No crosshair** — immersion-focused design using only weapon sights
- **Two weapon types** — pistol and rifle, each with unique animations and handling
- Full weapon control: switching, reloading, recoil, and ammo tracking

### 🧍 Character & Camera
- **True first-person perspective** — visible legs, hands, and body
- **Leaning mechanic** — left/right lean with preserved FOV and camera dynamics
- Custom animations for each movement and weapon state (idle, walk, run, etc.)

### 🎯 Levels
- **Firing Range** — timed run through a series of static targets
- **Training Arena** — moving targets with live accuracy tracking and scoring

### 🧩 HUD & Objectives
- Ammo count, objectives, and accuracy stats displayed in real-time
- Fully modular UI built with UMG and custom widgets
- Lightweight quest system to guide player through training phases

---

## 🛠️ Technologies Used

- **Unreal Engine 5.3** (Blueprint-only)
- **Animation System:**
  - Animation Blueprints (State Machines, Blend Spaces)
  - Control Rig + Sequencer-driven locomotion
  - Animation Montages, Aim Offset
  - Custom Animation Notifies for weapon states
- **Gameplay Mechanics:**
  - Weapon switching, recoil, ammo and reload systems
  - No-crosshair shooting with intuitive muzzle-based aiming
  - Blueprint-based quest and progression logic
- **UI / UX:**
  - UMG HUD: ammo display, objective tracker, accuracy feedback
  - Modular layout via custom widgets
- **Architecture:**
  - Blueprint Interfaces (BPI) for interactive systems
  - Clean modular structure with reusable components
- **Camera:**
  - First-person camera with visible full body
  - Dynamic leaning system with camera tilt and FOV adjustment
