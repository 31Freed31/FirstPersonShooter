# 🎯 First-Person Shooter Prototype — Unreal Engine 5

> Разработка: Blueprint-only | Движок: Unreal Engine 5.3  
> Тип проекта: Однопользовательский FPS с продвинутой системой стрельбы, кастомной анимацией и настраиваемым HUD

---

📖 Читайте на других языках: [🇬🇧 English](README.md)

## 📽️ Демо и сборка

- ▶️ [Видео-геймплей (YouTube)](https://your-youtube-link.com)
- 📦 [Скачать сборку (Google Drive)](https://your-google-drive-link.com)

---

## 🚀 Основные особенности

### 🎮 Стрельба и взаимодействие
- **Dead Zone Aiming** — оружие не привязано к центру экрана, прицеливание по ду́лу
- **Без прицела (crosshair)** — фокус на интуитивное прицеливание и контроль через мушку
- **2 типа оружия** — пистолет и автомат, каждый со своей анимацией и поведением
- **Полный контроль над оружием**: переключение, перезарядка, отдача, патроны

### 🧍 Персонаж и камера
- **True First-Person** — отображение тела, ног и рук от первого лица
- **Lean mechanic** — возможность наклоняться влево/вправо с сохранением FOV
- Персонализированная анимация в каждом состоянии: idle, бег, ходьба, оружие

### 🎯 Уровни
- **Полигон** — зачистка мишеней на время
- **Тренировочная арена** — динамичные мишени + система точности попаданий

### 🧩 HUD и квесты
- Отображение патронов, текущей задачи и статистики попаданий
- Модульный интерфейс через UMG и кастомные виджеты
- Мини-квестовая система: прохождение этапов и тренировки

---

## 🛠️ Используемые технологии

- Unreal Engine 5.3 (Blueprint-only)
- Animation System:
  - Animation Blueprints (State Machines, Blend Spaces)
  - Control Rig + Sequencer for locomotion
  - Animation Montages, Aim Offset
  - Custom Animation Notifies for weapon states
- Gameplay:
  - Weapon Switching, Recoil, Ammo & Reload Systems
  - No-crosshair shooting (intuitive muzzle-based aiming)
  - Quest System with progression logic
- UI / UX:
  - UMG HUD: ammo counter, objective tracker, accuracy stats
  - Custom Widgets with modular layout
- Architecture:
  - Blueprint Interfaces (BPI) for interaction
  - Clean modular structure with reusable components
- Camera:
  - True first-person view (visible body)
  - Lean mechanic with head movement and FOV handling

---

## 👤 Автор

**Разработчик**: Abdul  
📧 Контакт: your@email.com  
💼 GitHub: [@31Freed31](https://github.com/31Freed31)

