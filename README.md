# Hand Gesture LED Control

This project allows you to control 5 different LEDs using hand gestures. It uses **MediaPipe** for hand tracking and **pyserial** to communicate with an Arduino.

## Components
- Arduino Uno
- 5 LEDs & Resistors
- Webcam
- Python 3.x

## How to Run
1. Connect your Arduino to `COM5` (or update the port in `main.py`).
2. Upload `led_control.ino` to your Arduino.
3. Install required libraries:
   ```bash
   pip install -r requirements.txt
