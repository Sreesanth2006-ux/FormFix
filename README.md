# 🏋️‍♂️ FormFix AI — Interactive Prototype

FormFix AI is a web-based real-time form coaching assistant designed to watch your form through your device's camera and provide live feedback to prevent injuries during workouts.

This repository hosts a clean, interactive click-through prototype of the FormFix experience.

---

## 🚀 How to Open and Run

Since this prototype is a standalone, lightweight web application built with vanilla HTML, CSS, and JavaScript, **no setup, installation, or server is required**.

### Option 1: Run Locally (Quickest)
1. **Download/Clone** this repository.
2. Double-click the [`index.html`](file:///c:/Users/pkuma/Downloads/form%20fix/repo-clone/index.html) file to open it in any modern web browser (Chrome, Safari, Edge, Firefox).

### Option 2: Run via GitHub Pages
You can host this directly on GitHub Pages so anyone can open it via a public URL:
1. Go to your repository settings on GitHub.
2. Navigate to **Pages** in the sidebar.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Choose the `main` branch and folder `/ (root)`, then click **Save**.
5. Once built, it will be accessible at: `https://<your-username>.github.io/FormFix/`

---

## ✨ Features Included

* **🏋️ Exercise Selector**: Choose between bodyweight squats, push-ups, and lunges.
* **🎥 Live Camera Feed**: Directly accesses your browser's webcam (fully private, on-device only).
* **🤖 Simulated Skeleton Overlay**: Animates a real-time tracking skeleton overlay on the user's body.
* **💡 Real-time Coaching Feedback**: Dynamically displays coaching tips, rep counts, and a color-coded live Form Score ring.
* **📊 Post-Session Recap**: Detailed session summary showing your overall average form score, a canvas-rendered rep-by-rep score sparkline, and actionable coaching tips.

---

## 🛠️ Technology Stack

* **Structure**: Semantic HTML5
* **Styling**: Vanilla CSS3 (custom HSL color palette, smooth transition animations, responsive layout, glassmorphic UI elements)
* **Logic**: Vanilla JavaScript ES6 (modular state management, canvas rendering, device camera streaming, and dynamic SVG animations)

---

## 📝 Prototype vs. Production

> [!NOTE]
> * **Camera Privacy**: The camera stream runs purely in your local browser and is never sent to any server.
> * **Simulated Logic**: In this prototype, the skeleton overlay coordinates and coaching advice are simulated to demonstrate the user flow and design aesthetic.
> * **Production Plan**: The production build integrates on-device pose estimation (using TensorFlow.js MoveNet or MediaPipe) to track coordinates, feeding a lightweight rule engine and LLM coaching layer for authentic form analysis.