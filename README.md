# Hand Gesture Mouse Controller

A Python-based computer vision project that uses a webcam and hand gestures to control mouse actions. Leveraging **MediaPipe**, **OpenCV**, and **PyAutoGUI**, this application allows you to perform the following gestures:

- **Mouse Movement**
- **Left Click**
- **Right Click**
- **Double Click**
- **Take Screenshot**

## Features

- Real-time hand tracking using MediaPipe.
- Gesture recognition for:
  - Mouse movement (using index finger).
  - Left click (index finger bent, middle finger straight).
  - Right click (middle finger bent, index finger straight).
  - Double click (both index and middle fingers bent).
  - Screenshot (index and middle fingers bent and thumb close to index base).

## Demo

![Demo Screenshot](demo_screenshot.png) *(Replace with your image if needed)*

## Requirements

Install the following Python packages before running:

```bash
pip install opencv-python mediapipe pyautogui pynput numpy



FILE STRUCTURE
.
├── main.py              # Main script to run the gesture recognition
├── util.py              # Utility functions (angle, distance calculation)
├── README.md            # This file


GESTURE DEFINITION :
| Gesture        | Description                                         |
| -------------- | --------------------------------------------------- |
| Mouse Movement | Move index finger, thumb close to index base        |
| Left Click     | Index finger bent, middle finger straight           |
| Right Click    | Middle finger bent, index finger straight           |
| Double Click   | Both index and middle fingers bent                  |
| Screenshot     | Same as double click, but thumb close to index base |


Notes
Ensure good lighting conditions for accurate gesture detection.
Currently supports only one hand at a time.
Screenshots are saved in the current directory with filenames like my_screenshot_###.png.

License
This project is licensed under the MIT License. See LICENSE for more details.


Acknowledgments
MediaPipe
OpenCV
PyAutoGUI

