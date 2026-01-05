# 🎨 Air Canvas Using Computer Vision

An advanced **gesture-based drawing application** that allows users to draw in the air using hand movements captured via a webcam. Built using **OpenCV**, **MediaPipe**, and **Machine Learning (SVM)**, this project also supports **voice feedback**, **shape drawing**, **undo/redo gestures**, and **ASL Sign-to-Text recognition**.

---

## 🚀 Features

### ✋ Gesture-Based Drawing
- Draw in the air using your **index finger**
- **Thumbs Up** → Enable drawing  
- **Open Palm** → Stop drawing  
- **Thumbs Down** → Clear canvas  

### 🎨 Drawing Tools
- Freehand drawing
- Shape drawing:
  - Rectangle
  - Circle
  - Triangle
- Multiple brush types:
  - Round
  - Square
  - Dotted
  - Spray
  - Pattern
  - Star
- Adjustable brush sizes
- Preset & custom colors
- Eraser tool

### 🔁 Undo / Redo
- **Two-finger swipe left** → Undo
- **Two-finger swipe right** → Redo

### 💾 Save Canvas
- Press **`s`** key  
- Or show **Peace ✌️ sign**

### 🗣 Voice Feedback
- Real-time audio feedback for actions using **Text-to-Speech (pyttsx3)**

---

## 🤟 Sign-to-Text (ASL Recognition)

- Uses **MediaPipe hand landmarks**
- Trained using **Support Vector Machine (SVM)**
- Recognizes hand signs and converts them into text
- Draw recognized text directly on canvas

### Training Mode
- Press **`p`** → Toggle training mode
- Press **`a` – `z`** to collect ASL data
- Press **`m`** to train SVM model

---

## 🧰 Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Scikit-learn (SVM)
- pyttsx3 (Text-to-Speech)
- Multithreading & Queue

---

## 📂 Project Structure
```
Air-Canvas/
│
├── main.py # Main application file
```

---

## ⚙️ Installation
```bash
1️⃣ Clone the Repository
git clone https://github.com/7706manoj/air-canvas.git
cd air-canvas
2️⃣ Install Required Libraries
pip install opencv-python mediapipe numpy scikit-learn pyttsx3
▶️ How to Run
python main.py
⌨️ Keyboard Shortcuts
Key	Action
s	Save canvas
q	Quit application
h	Toggle help menu
b	Change brush type
1	Rectangle
2	Circle
3	Triangle
d	Text input mode
t	Toggle Sign-to-Text
p	Training mode
m	Train SVM model
🧠 Future Enhancements

Multi-hand support

More ASL gestures

UI-based toolbar (GUI)

Cloud-based model storage

Mobile / AR integration

👨‍💻 Author

Manoj
B.Tech Graduate | Computer Vision & Frontend Enthusiast
Project: Air Canvas Using Computer Vision
