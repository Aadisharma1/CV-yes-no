# CV-yes-no
👍👎 Thumbs Up/Down Gesture Recognition
This project is a simple hand gesture recognition model that detects whether a hand is showing a thumbs up (yes) or thumbs down (no) using a webcam. Built with MediaPipe, OpenCV, and a lightweight classification model, it's a fun and intuitive way to interact with your computer using hand signs.


🔍 Features
Real-time gesture recognition using your webcam

Detects thumbs up (yes) and thumbs down (no)

Uses MediaPipe Hands for hand tracking

Lightweight and fast — runs on most machines

🧠 How it Works
Captures video input using OpenCV

Detects hand landmarks using MediaPipe

Analyzes landmark positions to determine thumb orientation

Classifies the gesture as "yes" or "no"

🛠️ Requirements
Python 3.7+

OpenCV

MediaPipe

NumPy (if you're using it for any processing)

Install dependencies:

bash
Copy
Edit
pip install opencv-python mediapipe numpy
🚀 Getting Started
Clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/thumbs-gesture-recognition.git
cd thumbs-gesture-recognition
Run the program:

bash
Copy
Edit
python thumbs_detector.py
Wave your hand in front of the camera and try a 👍 or 👎!

📁 File Structure
bash
Copy
Edit
├── thumbs_detector.py   # Main script
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
🧪 Customization
You can tweak the model or logic in thumbs_detector.py to recognize other gestures or improve accuracy.

📸 Example Output
yaml
Copy
Edit
[INFO] Gesture detected: YES 👍
[INFO] Gesture detected: NO 👎
✅ Use Cases
Quick binary feedback in interfaces

Fun interactive games

Accessibility tools for simplified input

🙌 Acknowledgements
MediaPipe

OpenCV

Python Community 🐍

📃 License
MIT License. Feel free to use and modify!

