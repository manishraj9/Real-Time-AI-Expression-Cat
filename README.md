# 🐱 Expression Cat – AI-Powered Real-Time Emotion & Gesture Recognition

An interactive **AI-powered Computer Vision application** that detects a user's **facial expressions** and **hand gestures** in real time using a webcam, then synchronizes a virtual cat's expressions accordingly.

This project combines **Artificial Intelligence, Computer Vision, and Machine Learning** to create an engaging real-time interactive experience.

---

## 📸 Preview

## 😄 Smile Detection

The cat smiles when the user smiles.

📷 **Screenshot:** [😄 Smile Detection](assets/smile.png)

---

## 😉 Wink Detection

The cat winks when the user winks.

📷 **Screenshot:** [😉 Wink Detection](assets/wink.png)

---

## 👍 Thumbs-Up Gesture

The cat gives a thumbs-up when the user performs a thumbs-up gesture.

📷 **Screenshot:** [👍 Thumbs-Up Gesture](assets/thumbsup.png)

---

## 😲 Surprise Detection

The cat reacts with a surprised expression when the user makes a surprised face.

📷 **Screenshot:** [😲 Surprise Detection](assets/surprise.png)

---

## 😠 Angry Expression

The cat becomes angry when the user's facial expression is detected as angry.

📷 **Screenshot:** [😠 Angry Expression](assets/angry.png)
---

## 🎥 Demo

https://github.com/manishraj9/Real-Time-AI-Expression-Cat

*(You can also add a GIF or YouTube demo link here.)*

---

# ✨ Features

- 🧠 AI-Powered Facial Expression Recognition
- 😊 Smile Detection
- 😉 One-Eye Wink Detection
- 👍 Thumbs-Up Gesture Recognition
- 😲 Surprise Detection
- 😠 Angry Face Detection
- 📷 Real-Time Webcam Processing
- 🐱 Dynamic Cat Expression Mapping
- ⚡ Fast Real-Time Performance
- 💻 Interactive Desktop Application

---

# 🛠️ Tech Stack

### Language

- Python

### Artificial Intelligence

- DeepFace
- MediaPipe

### Computer Vision

- OpenCV

### Machine Learning

- TensorFlow Lite (used internally by MediaPipe)

### Libraries

- NumPy

---

# 📂 Project Structure

```
expression-cat/
│
├── animals/
│   ├── angry.png
│   ├── happy.png
│   ├── surprise.png
│   ├── wink.png
│   ├── thumbsup.png
│
├── main.py
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/manishraj9/expression-cat.git

cd expression-cat
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python main.py
```

---

# 🎮 How It Works

1. Open the application.
2. Allow webcam access.
3. The AI continuously analyzes your face and hand gestures.
4. When an expression or gesture is detected, the corresponding cat image is displayed instantly.
5. Press **Q** to close the application.

---

# 🧠 AI Workflow

```
Webcam
     │
     ▼
OpenCV
     │
     ▼
MediaPipe Face & Hand Detection
     │
     ▼
DeepFace Emotion Recognition
     │
     ▼
Expression Classification
     │
     ▼
Display Matching Cat Image
```

---

# 📸 Supported Expressions

| User Action | Cat Reaction |
|-------------|--------------|
| 😊 Smile | Smiling Cat |
| 😉 Wink | Winking Cat |
| 👍 Thumbs Up | Thumbs-Up Cat |
| 😲 Surprise | Surprised Cat |
| 😠 Angry | Angry Cat |

---

# 📦 Requirements

- Python 3.10+
- Webcam
- Windows / Linux / macOS

---

# 🔮 Future Improvements

- 😭 Sad Emotion
- 😂 Laugh Detection
- 😴 Sleepy Expression
- ❤️ Heart Eyes
- 👏 Clap Gesture
- 👋 Hand Wave Recognition
- 🎤 Voice Commands
- 📸 Screenshot Capture
- 🎥 GIF Recording
- 🌐 Web Version using Gradio or Streamlit

---

# 📚 Learning Outcomes

Through this project, I learned:

- Real-Time Computer Vision
- AI-Based Emotion Recognition
- Facial Landmark Detection
- Hand Gesture Recognition
- OpenCV Image Processing
- MediaPipe Integration
- DeepFace Integration
- Python Application Development

---

# ⚠️ Note

This project is a desktop application that requires access to the user's webcam. It is intended to run locally and is not directly deployable as a standard web application without architectural changes.

---

# 👨‍💻 Author

**Manish Raj**

🎓 B.Tech CSE

GitHub:
https://github.com/manishraj9

---

# ⭐ Support

If you enjoyed this project, please consider giving it a ⭐ on GitHub.

It helps support future AI and Computer Vision projects.
