# V-B-Control

## Hand Gesture Control for Volume and Brightness

**V-B-Control** is a cutting-edge project that enables users to control their computer's audio volume and screen brightness using intuitive hand gestures. Utilizing the Mediapipe library for real-time hand tracking, this application provides a seamless and interactive user experience, eliminating the need for traditional input devices.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Hand Gestures](#hand-gestures)
- [Customization](#customization)
- [Contributions](#contributions)
- [License](#license)
- [Contact](#contact)

## Overview
The **Hand Gesture Control** project leverages computer vision techniques to interpret hand movements captured by a webcam. By tracking hand landmarks, the system can distinguish between different gestures and perform corresponding actions such as adjusting the volume and brightness of the system.

## Application Goals
- Enhance user experience by allowing hands-free control of volume and brightness.
- Implement a responsive system that recognizes gestures with minimal latency.
- Provide visual feedback for real-time adjustments.

## Features
- **Volume Control**: Adjust your system's audio volume by manipulating your hand gestures.
- **Brightness Control**: Change the screen brightness with simple hand movements.
- **Real-Time Feedback**: Visual indicators show current volume and brightness levels directly on the screen.
- **Customizable Parameters**: Modify settings to optimize gesture sensitivity and recognition based on personal preferences.

## Requirements
To run this project, ensure you have the following libraries and tools installed:

- Python 3.x
- OpenCV (cv2)
- Mediapipe
- ctypes
- comtypes
- pycaw
- wmi
- win32api

## Installation
Install the necessary libraries using pip:
bash
pip install opencv-python mediapipe comtypes pycaw wmi pywin32

## Usage

Clone the Repository: Start by cloning the repository to your local machine:

git clone https://github.com/Venomous000/V-B-Control.git

Navigate to the Project Directory: Change your working directory to the cloned project:

cd V-B-Control,

Run the Application: Launch the script using Python:

python hand_gesture_control.py

Position Your Hand: Stand in front of your webcam and use your hands to control volume and brightness as per the gestures defined below.

## Hand Gestures

Volume Control:
Increase Volume: Bring your thumb and index finger closer together on the left side of the screen.
Decrease Volume: Move your thumb and index finger further apart on the left side.

Brightness Control:
Increase Brightness: Bring your thumb and index finger closer together on the right side of the screen.
Decrease Brightness: Move your thumb and index finger further apart on the right side.

## Customization

You can fine-tune the following parameters within the code to better suit your environment and preferences:
model_complexity: Adjusts the complexity of the hand tracking model. A higher value increases detection accuracy but may require more processing power.
min_detection_confidence: Sets the minimum confidence level for detecting hands. Increase this value for better accuracy but may miss some gestures.
min_tracking_confidence: Defines the minimum confidence level required for tracking hand landmarks.
brightFactor: Alters the sensitivity of brightness adjustments based on hand gestures.

## Contributions
Contributions are highly encouraged! If you have suggestions for improvements, feature requests, or bug reports, please create an issue or submit a pull request. Your feedback is invaluable in making this project better.
