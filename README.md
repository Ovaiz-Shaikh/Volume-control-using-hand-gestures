# Volume-control-using-hand-gestures

🔊 Hand Gesture Volume Controller
Control your system volume using hand gestures with the help of OpenCV, MediaPipe, and Pycaw! This real-time computer vision project uses your webcam to track hand landmarks and adjusts volume based on the distance between your thumb and index finger.

# 📸 How It Works:

The webcam captures your hand in real-time.

The program detects landmarks using MediaPipe.

It calculates the distance between the thumb tip and index finger tip.

This distance is mapped to system volume range.

Volume changes dynamically as you pinch/open your fingers.



# ▶️ Instructions to Run
1. Clone the repo

 git clone https://github.com/Ovaiz-Shaikh/Volume-control-using-hand-gestures.git

 cd hand-gesture-volume-control

2. Install dependencies
 Use pip to install required libraries:

 pip install opencv-python mediapipe pycaw numpy comtypes

 🔐 Note: Pycaw works only on Windows as it uses Windows Core Audio APIs.

3. Run the program
 
      python Volume_Control.py

      Make sure your webcam is connected and your system audio is not muted.
