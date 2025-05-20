# 🎹 Piano Visual Playground

An interactive audiovisual project built with [p5.js](https://p5js.org/), [p5.sound](https://p5js.org/reference/#/libraries/p5.sound), and [Tweakpane](https://cocopon.github.io/tweakpane/). This creative coding experience lets you play a virtual piano or watch visuals respond to recorded songs like *Clair de Lune* and *Gymnopédie*.

---

## 🌟 Features

- 🎼 Play piano keys on your keyboard (A–L, W–P)
- 🖼️ 4 unique visual modes:
  - **Flow Field**
  - **Liquid Drip**
  - **Harmonic Sands**
  - **Waveform Terrain**
- 🎵 Visuals react to both:
  - **Live piano key input**
  - **Preloaded recorded music**
- 🎛️ Tweakpane UI to control:
  - Music selection
  - Volume
  - Visual behavior (e.g. wave height, flow speed)

---

## 🎮 How to Use

### 🎨 Visual Mode Selection:
From the **main menu**, press one of the following keys to enter a visual mode:

- `1` → **Flow Field**
- `2` → **Liquid Drip**
- `3` → **Harmonic Sands**
- `4` → **Waveform Terrain**

- `ESC` → Return to menu  
- `Enter` or `Return` → Restart the current visual

---

### 🎹 Piano Controls:

Use your keyboard to play notes. These trigger both **sound** and **visual effects**.

| Keyboard Key   | Note Played |
|----------------|-------------|
| A, S, D, F, G, H, J, K, L, ;, ' | C4 to F5 (natural notes) |
| W, E, R, T, Y, U, I, O, P       | Sharps/flats (Db4 to Ab5) |


### 🎛️ Tweakpane Controls:

Press lowercase `v` to toggle the settings panel (top-right corner). It includes:

- **Music Track**: dropdown list of preloaded MP3s
- **Control**: Play / Pause / Restart the selected track
- **Volume**: Adjust playback volume
- **Flow Speed**: Controls speed of particles (Flow Field mode)
- **Wave Height**: Controls size of wave layers (Waveform mode)

> ✅ Visuals respond to the volume of the music in real time.

---


---

## 🚀 How to Run Locally

1. Download or clone this repo
2. Open the project in VSCode
3. Right-click index.html and choose **"Open with Live Server"**
4. Press keys or select music to interact
If you don’t have Live Server installed, you can install it from the Extensions tab in VS Code (ritwickdey.LiveServer).
