---

# 📐 SitRight — Real-Time Posture Checker

SitRight helps you maintain healthy posture while working.
It uses a **lightweight real-time ML model in the browser** to detect slouching, leaning, and neck bend — and guides you back to a neutral spine.

---

link: https://www.youtube.com/watch?v=In6uUomj5kw

## ✨ Features

* 🎥 **Real-time webcam posture tracking (no uploads)**
* 🤖 **Runs fully in-browser** — no server, no data stored
* ⚠️ **Instant alerts** when posture becomes unhealthy
* 🚀 **Fast + lightweight model optimized for the web**

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **ML:** Custom model exported for browser inference (TensorFlow.js / ONNX runtime Web)
* **Posture Logic:** Trained on wrong and right posture datasets

---

## 📦 Installation

> Clone the repo

> Run locally from index.html 🙂

---

## ▶️ How It Works

1. Turn on webcam in your browser
2. ML model detects keypoints (head, shoulders, spine alignment)
3. App computes:

   * Back angle
   * Neck tilt
   * Shoulder level
4. If angles exceed allowed thresholds → **alert triggered**


## 🛣️ Roadmap

* 🪑 Desk height recommendation mode
* 🎧 Audio alert
* 📈 Weekly posture analytics with insights

---

## 🤝 Contributing

Pull requests welcome!
Open an issue if you find bugs or want a feature.

---

## 📄 License

MIT License

---
