## Features

- Detects and tracks hand landmarks in real time.
- Recognizes left and right-hand gestures for mouse and keyboard control.
- Control the mouse cursor and perform keyboard actions (e.g., move, click, swipe) using hand gestures.
- Easily customizable for different hand gestures and actions.

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- PyAutoGUI (`pip install pyautogui`)

## Hand Gestures and Actions

- **Left Hand (Mouse Control):**
  - Move your left hand to control the mouse cursor.
  - When the index finger tip is above the index finger middle, it simulates a left mouse click.

- **Right Hand (Keyboard Control):**
  - Move your right hand to control the keyboard.
  - Swipe right or left to simulate arrow key presses ('right' or 'left').
  - Swipe up or down to simulate arrow key presses ('up' or 'down').

