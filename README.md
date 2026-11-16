# neon-breaker# NEON BREAKER — Cyberpunk Arcade

A high-speed, single-file cyberpunk brick-breaker built with HTML5 Canvas, Tailwind CSS, and the Web Audio API. Smash through symmetrical neon formations, trigger chain-reaction bomb explosions, and stack massive combo multipliers across infinite stages.

## 🎮 Features

* **Infinite Level Progression:** Battle through **5 handcrafted symmetrical stages** (Cyber Diamond, Twin Towers, Neon Fortress, Vortex Grid, and Overdrive Citadel), followed by **endless procedurally generated symmetrical waves** (Stage 6+) with scaling speed and tougher brick layouts.
* **4 Distinct Brick Types:**
  * **Standard Bricks (1 HP):** Classic neon targets worth 100 base points.
  * **Reinforced Armor Bricks (2 HP):** Heavy magenta plating that visibly cracks upon taking damage (200 base points).
  * **Heavy Core Bricks (3 HP):** Multi-layered energy cores requiring three hits to shatter (350 base points).
  * **Bomb Bricks (1 HP):** Detonates in an explosive shockwave that destroys all adjacent bricks in a chain reaction (250 base points).
* **5 Power-Ups with Live HUD Timers:**
  * **`M3` Multi-Ball:** Splits active balls into 3 spread balls (up to 9 balls on screen at once).
  * **`FIRE` Fireball (8s):** Superheats your balls so they pierce straight through bricks without bouncing.
  * **`LASER` Laser Paddle (10s):** Mounts twin turrets on your paddle that automatically fire upward laser bolts.
  * **`WIDE` Wide Paddle (12s):** Expands your paddle width by 50% for easier rebounds.
  * **`+1UP` +1 Shield:** Restores an extra shield life (up to 5 max, or awards +1,000 points if shields are already full).
* **Combo Multiplier System:** Every consecutive brick hit before touching the paddle increases your score multiplier (`2x`, `3x`, `4x`...) with ascending pentatonic synth notes.
* **Built-In Retro Audio Synthesizer:** Procedural Web Audio API sound effects for bounces, shatters, explosions, lasers, and stage clears—no external audio files required.
* **Local High Score Persistence:** Automatically saves your all-time best score in your browser.

## 🕹️ Controls

### Desktop
* **Move Paddle:** `Mouse` or `A` / `D` / `Left` / `Right` Arrow keys
* **Launch Ball:** `Spacebar` or `Left Click`
* **Pause / Resume:** `P` or `Esc`
* **Mute / Unmute Audio:** `M`

### Mobile & Touch
* **Move Paddle:** Touch and drag anywhere on the screen
* **Launch Ball:** Tap or release your finger


3. Click **Start Game** to launch into Stage 1!

## 🛠️ Tech Stack
* **HTML5 Canvas API** (Sub-stepped collision physics, motion trails, and particle effects)
* **Vanilla JavaScript (ES6+)**
* **Web Audio API** (Real-time retro sound synthesis)
* **Tailwind CSS** (Loaded via CDN for responsive HUD and modal overlays)
