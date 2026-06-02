# Gesture-Cam



## ✨ Features

| Prompt | Feature | Implementation |
|--------|---------|----------------|
| **Prompt 1** | Fullscreen webcam + white dot on index fingertip | MediaPipe Hands tracks 21 landmarks, a glowing white dot follows your index fingertip in real-time |
| **Prompt 2** | Detect 4 gestures from 21 landmarks | Fist ✊, Peace Sign ✌️, Index Finger ☝️, Open Hand 🖐️ |
| **Prompt 3** | Map gestures to visual filters | ✊ **Dither** (retro pixelated scanlines) / ✌️ **VHS + Chromatic Aberration** (RGB shift + noise) / ☝️ **Spotlight** (follows your fingertip) / 🖐️ **Water Ripple** (distortion waves from center) |

---

## 🎨 Design Highlights

- **Dark cinematic UI** with gradient overlays, corner brackets, and monospace typography
- **Real-time status badge** showing tracking state
- **Active gesture cards** at the bottom highlight which gesture is detected
- **Hand skeleton overlay** drawn with glowing green lines on the 21 MediaPipe landmarks
- **Smooth transitions** between filters with no jarring cuts
- **FPS counter** for performance monitoring
- **Loading screen** with animated spinner and start button for camera permission

---

## 🚀 How to Use

1. **Download the file** below
2. **Open in any modern browser** (Chrome/Edge/Firefox)
3. **Click "Start Experience"** to allow camera access
4. **Show your hand** to the camera and try the 4 gestures!
5. The white dot tracks your index finger, and filters apply instantly

---

## 📥 Download

**[GestureCam — Hand Tracking Visual Filters](sandbox:///mnt/agents/output/gesturecam.html)**

> The file is a single self-contained HTML file. It loads MediaPipe Hands from CDN, so an internet connection is required on first load. All processing happens locally in your browser — no video data is sent to any server.
