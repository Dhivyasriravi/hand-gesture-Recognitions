# 🖐️ Hand Gesture Recognition System

> Real-time hand gesture detection using TensorFlow.js — runs entirely in the browser, no installation required.

**Built by:** Dhivyasri Ravi | CSE Graduate 2026

---

## 🚀 Live Demo
[View Live](https://yourusername.github.io/hand-gesture-recognition)

---

## 📌 About the Project
A real-time hand gesture recognition system that uses the webcam to detect hand gestures and maps them to actions like Play/Pause, Next Slide, Volume Control, and Stop — all running 100% in the browser using TensorFlow.js HandPose model.

---

## ✨ Features
- 🎥 Real-time webcam-based hand detection
- 🖐️ Detects 6 unique hand gestures
- ⚡ Maps gestures to real actions (Play/Pause, Next/Prev Slide, Volume Up/Down, Stop)
- 📊 Live FPS counter and detection confidence bar
- 🕓 Gesture history log with timestamps
- 🔵 Visual hand skeleton overlay on webcam feed
- 💻 Works 100% in browser — no Python, no installation

---

## 🖐️ Supported Gestures

| Gesture | Action |
|---|---|
| ✋ Open Palm | ▶ Play / Pause |
| ☝️ Index Finger Up | ⏭ Next Slide |
| ✌️ Peace / V Sign | ⏮ Previous Slide |
| ✊ Fist | ⏹ Stop |
| 👍 Thumbs Up | 🔊 Volume Up |
| 👎 Thumbs Down | 🔇 Volume Down |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 / CSS3 / JavaScript | Frontend |
| TensorFlow.js | AI/ML inference in browser |
| HandPose Model | Hand landmark detection |
| Canvas API | Real-time skeleton overlay |

---

## ⚙️ How to Run

### Option 1 — Direct (Simplest)
```bash
1. Download hand_gesture_recognition.html
2. Open in Google Chrome
3. Allow camera permission
4. Wait ~20 seconds for model to load
5. Show your hand to the webcam!
```

### Option 2 — VS Code Live Server (Recommended)
```bash
1. Install VS Code + "Live Server" extension
2. Open the HTML file in VS Code
3. Right-click → "Open with Live Server"
4. Opens at localhost:5500 in Chrome
```

### Option 3 — GitHub Pages (Deploy Online)
```bash
1. Create GitHub repo: hand-gesture-recognition
2. Upload file, rename to index.html
3. Settings → Pages → main branch → Save
4. Live at: https://yourusername.github.io/hand-gesture-recognition
```

---

## 📁 Project Structure
```
hand-gesture-recognition/
│
├── index.html        ← Complete project (single file)
└── README.md         ← Documentation
```

---

## 🧠 How It Works
1. Webcam feed is captured using `getUserMedia` API
2. Each frame is passed to TensorFlow.js HandPose model
3. Model returns 21 3D hand landmarks
4. Custom algorithm classifies landmark positions into gestures
5. Detected gesture triggers the mapped action

---

## 📸 Screenshots
> Add screenshots of the project running here

---

## 🔮 Future Improvements
- [ ] Add more gestures (rock, call me, OK sign)
- [ ] Connect to real media player controls
- [ ] Add multi-hand detection support
- [ ] Mobile/tablet support

---

## 👩‍💻 Author
**Dhivyasri Ravi**
- 📧 dhivyasriravi5@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/dhivyasri)
- 💻 [GitHub](https://github.com/dhivyasri)

---

## 📄 License
MIT License — free to use and modify.
