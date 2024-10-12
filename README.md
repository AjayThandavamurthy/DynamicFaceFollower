# DynamicFaceFollower

DynamicFaceFollower is a face tracking project that uses OpenCV for real-time face detection via a webcam and controls servos to follow the detected face. This project can be integrated with Arduino to create a dynamic face-following mechanism.

## Features

- Real-time face detection using Haar Cascade Classifier.
- Dynamic servo control to follow the face's movement.
- Communication between Python and Arduino via Serial.

## Requirements

### Hardware

- Webcam
- Arduino (with compatible servos)
- Two servos for horizontal and vertical movement

### Software

- Python 3.x
- OpenCV
- NumPy
- Arduino IDE
- VarSpeedServo library for Arduino
