
Air Canvas Using Computer Vision 🎨
An innovative gesture-based drawing platform that allows users to draw, write, and interact with a virtual canvas using hand gestures captured via a webcam. The system integrates real-time hand tracking, gesture recognition, and American Sign Language (ASL) support using computer vision.

✨ Features:
🎥 Real-Time Hand Tracking using MediaPipe and OpenCV.
✋ Gesture-Based Drawing: Draw using finger movements in mid-air.
🖌️ Brush Customization: Supports multiple brush types, colors, and sizes.
🔄 Undo/Redo and Save: Perform canvas actions via simple hand gestures.
📐 Shape Drawing: Gesture-based drawing of geometric shapes.
🔡 ASL Recognition: Recognizes static ASL signs and converts them to text.
🔊 Voice Feedback: Optional text-to-speech support for ASL output.
💻 Lightweight: Runs on standard laptops without the need for GPUs.

📚 Technologies Used:
Python
OpenCV
MediaPipe
Scikit-learn (SVM for ASL recognition)
NumPy
pyttsx3 (Text-to-Speech)

🎯 Objectives:
Enable touch-free, intuitive digital drawing using webcam-based hand tracking.
Support gesture-based commands for shape drawing, erasing, undo/redo, and more.
Integrate ASL sign-to-text recognition for accessibility.
Provide real-time performance on low-spec hardware.

✋ Gesture Commands:
Gesture	Action
Thumbs Up	Enable Drawing
Open Palm	Disable Drawing
Thumbs Down	Clear Canvas
Peace (V Sign)	Save Canvas
Two Finger Swipe	Undo/Redo Strokes

🔤 ASL Recognition:
Recognizes static ASL alphabets using a trained SVM model.
Provides visual and optional voice feedback.

🎨 Toolbar Options:
Color Selection
Brush Size Adjustment
Eraser
Mode Switching (Freehand/Shape)
