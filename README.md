# 🐦 Flippy Floppy – Flappy Bird Style Game

A fast-paced, one‑file HTML5 game inspired by Flappy Bird. Control the bird, dodge pipes, and get the highest score. Built for hackathons – **no dependencies, runs in any browser**.

## 🎮 How to Play

- **Goal**: Fly through as many pipe gaps as possible. Each pipe pair passed gives **+1 point**.
- **Controls**:
  - **Click** on the game canvas
  - **Press Spacebar**
  - **Press Arrow Up**
- **Game Over**: Hit the ground, ceiling, or any pipe.
- **Restart**: Click the **FLAP AGAIN** button or press any control after game over.

# **Note**: **If you see the first pipe blocked, then try refreshing the page.**

## 🚀 Getting Started

1. Save the game code as `flippy_floppy.html.`
2. Double‑click the file – it opens in your default web browser.
3. Start flapping!

> No internet connection or external libraries required.

## 🧠 Game Mechanics

- **Gravity & Flap**: The bird falls naturally; each flap gives an upward boost.
- **Pipe Gap**: Fixed at **190px** – comfortably wider than the bird (40px tall) for fair play.
- **Increasing Speed**: Every 5 points, the scroll speed increases slightly, making the game progressively harder.
- **Score Display**: Shows your current score at the top‑left and in the bottom panel.

## 🛠️ Customization (Easy Tweaks)

Open the file in any text editor and adjust these constants at the top of the `<script>`:

```javascript
const GRAVITY = 0.2;        // Lower = lighter gravity
const JUMP_POWER = -5.5;    // More negative = stronger flap
const PIPE_GAP = 190;       // Increase for easier gameplay
const PIPE_SPACING = 230;   // Distance between pipe pairs
const GROUND_LEVEL = H-65;  // Raise/lower the ground
