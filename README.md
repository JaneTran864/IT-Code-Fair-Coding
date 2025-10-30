# 🎥 **Gesture Trainer** — *Train Your Own Action Recognition Model in Minutes*  

**No coding. No setup. Just record, train, and use.**  

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oUZ8oPbDD37RU9o6sNpXI27t2_rHDFof)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
![Python](https://img.shields.io/badge/python-3.9%2B-blue)  
![Gradio](https://img.shields.io/badge/Gradio-Interactive-orange)

---

## 🌟 **Why This Exists**

> **"I want my computer to recognize *my* gestures — like waving, clapping, or sign language — without being a programmer."**

**Gesture Trainer** makes this possible.

- Record short video clips of **your own actions**  
- Click **"Train"** — no code, no terminal  
- Use the model **live in your webcam**  
- All in **Google Colab + your browser**

Perfect for:  
✅ Educators  
✅ Students  
✅ Sign language learners  
✅ Makers & hobbyists  
✅ Anyone curious about computer vision

---

## 🚀 **Live Demo (Try It Now!)**

👉 [**Open in Google Colab**](https://colab.research.google.com/drive/1oUZ8oPbDD37RU9o6sNpXI27t2_rHDFof)  
*(Click the badge above — no install needed)*

> **Just allow webcam access and follow the tabs!**

---

## 🎯 **How It Works (3 Simple Steps)**

| Step | What You Do |
|------|-------------|
| **1. Collect** | Record 10–30 short clips of each gesture ("hello", "thanks",...) |
| **2. Train** | Click **"Train LSTM"** — takes 10–60 seconds |
| **3. Test Live** | See real-time recognition with **landmarks + confidence bars** |

---

## 🖼️ **Screenshots**

| Collect Tab | Train Tab | Live Recognition |
|------------|-----------|------------------|
| ![Collect](screenshots/collect.png) | ![Train](screenshots/train.png) | ![Live](screenshots/live.gif) |

---

## 🛠️ **Tech Behind the Magic**

| Component | Role |
|---------|------|
| **MediaPipe Holistic** | Detects pose, face, and hand landmarks in real-time |
| **LSTM Neural Network** | Learns temporal patterns from keypoint sequences |
| **Gradio** | Beautiful, interactive web UI in your browser |
| **Google Colab** | Free GPU + no setup |

> **No Docker. No CUDA. No `pip install hell`.**

---

## 📋 **Quick Start Guide**

1. **Open the Colab notebook** (link above)
2. **Run all cells** (`Runtime > Run all`)
3. **Go to Tab 1: Collect**
   - Type action name: `wave`
   - Record 20 clips (5–10 seconds each)
4. **Go to Tab 2: Train**
   - Click **"Train LSTM"**
   - Wait ~30 seconds
5. **Go to Tab 3b: Live Test**
   - Click **"Load Latest Model"**
   - Wave at your webcam → see it recognised!

---

## 🎨 **Custom Actions You Can Teach**

| Action | Use Case |
|-------|----------|
| `hello` | Greeting detection |
| `thanks` | Gratitude in sign language |
| `stop` | Safety gesture |
| `dance_move_1` | Choreography tool |
| `exercise_squat` | Fitness tracker |

> **Teach *any* repeatable motion!**

---

## 💡 **Tips for Best Results**

- **Good lighting**, face the camera
- **Consistent background**
- **Same distance** from camera
- **10+ clips per action** (more = better)
- **Short clips** (3–10 seconds)

---

## 🔄 **Workflow for Non-Technical Users**
![](screenshots/workflow.png) 

## 🔒 **Your Data Stays Private**

- All videos processed locally in your browser/Colab
- Nothing uploaded to servers
- You own the model and data

## 🤝 **Contribute**
We welcome:

- New UI translations
- Pre-trained models (sign language)
- Mobile export (TensorFlow Lite)
- More action templates

Just open an issue or PR!

## ✨ **Made With ❤️ for Accessible Computer Vision**

> **"Computer Vision shouldn't require a PhD. It should require curiosity."**

Let’s bring computer vision to everyone.


