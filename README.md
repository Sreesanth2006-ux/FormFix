#  FormFix AI — Interactive Prototype

FormFix AI is a web-based real-time form coaching assistant designed to watch your form through your device's camera and provide live feedback to prevent injuries during workouts.

---

## 🔗 Try It Live

> **Open directly in your browser — no install needed:**
>
> ### 👉 [https://sreesanth2006-ux.github.io/FormFix/](https://sreesanth2006-ux.github.io/FormFix/)

Works on mobile and desktop. Just allow camera access when prompted.

---

## 🚀 How to Run Locally (Optional)

If you'd prefer to run it offline:
1. **Clone** this repository or [download the ZIP](https://github.com/Sreesanth2006-ux/FormFix/archive/refs/heads/main.zip).
2. Unzip and **double-click `index.html`** to open in any modern browser (Chrome, Safari, Edge, Firefox).

---

## ✨ Features Included

* **🏋️ Exercise Selector** — Choose between bodyweight squats, push-ups, and lunges.
* **🎥 Live Camera Feed** — Accesses your webcam directly in the browser (fully private, on-device only).
* **🤖 Simulated Skeleton Overlay** — Animates a real-time tracking skeleton overlay on the user's body.
* **💡 Real-time Coaching Feedback** — Coaching tips, rep counts, and a color-coded live Form Score ring.
* **📊 Post-Session Recap** — Average form score, a rep-by-rep score sparkline, and actionable tips.

---

## 🛠️ Technology Stack

* **Structure**: Semantic HTML5
* **Styling**: Vanilla CSS3 (custom color palette, smooth animations, responsive layout)
* **Logic**: Vanilla JavaScript ES6 (canvas rendering, device camera streaming, SVG animations)

---

## 📝 Prototype vs. Production

> [!NOTE]
> * **Camera Privacy**: The camera stream runs purely in your local browser and is never sent to any server.
> * **Simulated Logic**: In this prototype, the skeleton overlay and coaching advice are scripted to demonstrate the UX flow.
> * **Production Plan**: The production build integrates on-device pose estimation (TensorFlow.js MoveNet or MediaPipe) feeding a lightweight rule engine and LLM coaching layer for real form analysis.
