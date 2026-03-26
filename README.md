Hand Gesture-Based Volume Control System

Overview

This project is a Hand Gesture-Based Volume Control System that allows users to control their system volume using simple hand gestures. It uses computer vision techniques to detect hand movements through a webcam and adjusts the volume accordingly in real time.

Features

  * Real-time hand tracking using webcam
  * Gesture-based volume control
  * Visual feedback with volume bar and percentage
  * Touchless and user-friendly interaction
  * Works on macOS using system-level commands

Technologies Used

  * Python
  * OpenCV
  * MediaPipe
  * OS (AppleScript for macOS)

Installation

1. Create virtual environment

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies

```bash
pip install opencv-python mediapipe
```

Usage

Run the program:

```bash
python handtracking.py
```

Controls:

  * Move fingers **apart** → Increase volume 🔊
  * Move fingers **closer** → Decrease volume 🔉
  * Press **ESC** → Exit program

Output

  * Webcam window opens
  * Hand landmarks are displayed
  * Volume bar updates in real time
  * Volume changes based on finger distance

Requirements

  * Webcam
  * Python 3.10 or 3.11 (recommended)
  * macOS (for AppleScript volume control)

Limitations

  * Requires good lighting conditions
  * Works best with single hand
  * Limited gesture recognition

Future Improvements

  * Add gesture controls for play/pause
  * Implement smooth volume control
  * Support multiple gestures
  * Cross-platform support (Windows/Linux)

Author

  Subash Rahul

Acknowledgment

  This project is inspired by advancements in computer vision and gesture-based interaction systems.

License

  This project is for educational purposes.
