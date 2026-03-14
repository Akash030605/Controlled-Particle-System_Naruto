# Gesture Controlled Particle System

A real-time **gesture-controlled particle visualization system** built for the browser.  
This project renders large-scale particle simulations that dynamically change based on hand gestures detected from a webcam.

The system focuses on **GPU-accelerated particle effects**, smooth particle transitions, and interactive graphics using modern web technologies.

---

## Demo

Show hand gestures to activate different particle formations.

Examples of particle behaviors:

- Spiral particle sphere
- Electric burst particle field
- Radial eye-like particle structures
- Neutral floating particle cloud

Particles smoothly transition between these formations using interpolation.

---

## Tech Stack

- **JavaScript**
- **Three.js** – WebGL-based 3D rendering
- **MediaPipe Hands** – Real-time hand landmark detection
- **WebGL** – GPU accelerated particle rendering
- **EffectComposer + Bloom** – visual glow effects

---

## How It Works

1. Webcam input is captured from the browser.
2. **MediaPipe Hands** detects hand landmarks (21 points per hand).
3. Finger positions are analyzed to identify gestures.
4. Each gesture maps to a **particle generator function**.
5. Particle positions, colors, and sizes are updated dynamically.
6. Smooth interpolation transitions particles between formations.

The system currently renders around **20,000 particles in real time**.

---

## Particle Techniques

| Gesture | Particle Behavior |
|-------|------|
| Pinch | Electric particle burst |
| Open Hand | Spiral particle sphere |
| Two Fingers | Rotating radial pattern |
| Three Fingers | Complex rotating particle structure |

---

## Features

- Real-time gesture recognition
- Large-scale particle systems (~20k particles)
- GPU accelerated rendering
- Smooth particle transitions
- Post-processing glow effects
- Interactive visual feedback

---

## What I Learned

Building this project helped me understand:

- Designing and optimizing **large particle systems**
- Using **WebGL through Three.js**
- Connecting **computer vision outputs to graphics systems**
- Managing real-time animations efficiently
- Implementing **gesture-driven interactions**
- Enhancing visuals using **post-processing effects**

I also used **Google Gemini** during development to explore particle system ideas and assist with debugging and optimization.

---

## Run Locally

Clone the repository:

```bash
git clone https://github.com/Akash030605/Controlled-Particle-System_Naruto.git
```

Open the project folder and run it with a local server.

Example:

```bash
npx serve
```

Then open:

```
http://localhost:3000
```

Allow webcam permissions when prompted.

---

## Future Improvements

- Multiple hand detection
- More complex gesture combinations
- Custom particle shaders
- Audio-reactive particles
- Performance optimization for mobile

---

## Inspiration

This project explores the intersection of:

- **Computer Vision**
- **Creative Coding**
- **Interactive Graphics**
- **Real-Time WebGL Visualization**

---

## License

MIT License

