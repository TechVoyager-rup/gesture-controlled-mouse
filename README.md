---

# Gesture-Controlled Mouse Using Hand Tracking

Control your computer's mouse with hand gestures using computer vision and AI!

## Overview

This project leverages computer vision techniques using OpenCV and Mediapipe to enable gesture-based mouse control. It detects hand movements via webcam and translates them into various mouse actions, such as cursor movement, clicks, and screenshots, providing a hands-free, interactive experience.

## Features

- **Real-Time Hand Detection**: Utilizes Mediapipe to detect and track hand landmarks in real-time.
- **Mouse Actions**:
  - **Move Cursor**: Maps index finger movement to cursor position.
  - **Left Click**: Performs a left-click with a specific gesture.
  - **Right Click**: Executes a right-click with another gesture.
  - **Double Click**: Recognizes a double-click gesture.
- **Customizable Gestures**: Adjust gesture definitions, sensitivity, and actions.
- **Real-Time Feedback**: Displays recognized gestures on the video feed.

## Prerequisites

- Python 3.x
- Required Libraries: OpenCV, Mediapipe, PyAutoGUI, Pynput

Install dependencies using:

```bash
pip install opencv-python mediapipe pyautogui pynput
```

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/TechVoyager-rup/gesture-controlled-mouse.git
   cd gesture-controlled-mouse
   ```

2. Run the script:

   ```bash
   python main.py
   ```

3. Use your hand gestures in front of the webcam to control the mouse!

## Gesture Guide

- **Move Cursor**: Bend the Thumb inwards and move your Index finger or both the Index and Middle finger together.
- **Hold or stop the cursor movement**: Release the Thumb.
- **Left Click**: Bend your Index finger.
- **Right Click**: Bend your Middle finger.
- **Double Click**: Bend both the Index and the Middle finger together.

## Future Enhancements

- Add support for multi-hand gestures.
- Optimize gesture recognition for different lighting conditions.
- Expand functionality for additional custom gestures.

## Acknowledgments

- [Mediapipe](https://mediapipe.dev/)
- [OpenCV](https://opencv.org/)

---
