# ✨ Two-Hand Particle Gesture System

A browser-based interactive particle visualizer controlled with hand gestures through the webcam.

The project uses **Three.js** for the particle scene and **MediaPipe Hands** for real-time hand tracking. Everything runs from a single HTML file.

---

## 🚀 Features
- 20,000 animated particles rendered with Three.js.
- Webcam-based hand tracking with MediaPipe Hands.
- Gesture-controlled particle shapes:
  - Closed hand: compact cloud
  - One open hand: spiral
  - Two open hands: sphere
  - Two OK/pinch gestures: burst effect
- Hand position controls the particle system position.
- Hand height and spacing influence particle color and scale.

---

## 🗂️ Repository Structure

```text
particle.html
README.md
```

---

## ▶️ How to Run

1. Open `particle.html` in a modern browser.
2. Allow camera access when prompted.
3. Keep both hands visible to the webcam for best tracking.

If your browser blocks camera access from a local file, serve the folder locally instead:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/particle.html
```

---

## 🛠️ Tech Stack
- HTML, CSS, JavaScript
- Three.js
- MediaPipe Hands
- WebRTC camera access

---

## ⚠️ Notes
- The page loads Three.js and MediaPipe from public CDNs, so an internet connection is required.
- Camera permission is required for gesture control.
- Good lighting and a plain background improve hand-tracking quality.

---

## 🚀 Future Improvements
- Add on-screen gesture hints.
- Add mobile/touch fallback controls.
- Add performance settings for low-power devices.
- Split JavaScript and styles into separate files as the project grows.
