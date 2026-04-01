# Hand Gesture LED Control

This project allows you to control 5 different LEDs using hand gestures. It uses **MediaPipe** for hand tracking and **pyserial** to communicate with an Arduino.

## Components
- Arduino Uno
- 5 LEDs & Resistors
- Webcam
- Python 3.x

## How to Run
-Connect your Arduino to COM5
(or update the port in main.py)
-Upload led_control.ino to your Arduino
-Install required libraries:
pip install -r requirements.txt
-Run the project:
python main.py
