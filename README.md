AI Sign-Free Communication Support System

Overview

The AI Sign-Free Communication Support System is a deep learning project designed to support people who experience difficulty communicating verbally. It recognizes predefined hand gestures using MediaPipe and an LSTM neural network and displays the corresponding messages on the screen.

Objectives

- Recognize hand gestures in real time.
- Convert recognized gestures into meaningful messages.
- Explore computer vision and deep learning for accessible communication.

Gestures Supported

Gesture| Message
Water| I need water
Help| Please help me
Nurse| Please call the nurse
Pain| I am feeling pain
Yes| Yes
No| No

Technologies Used

- Python – Main programming language
- MediaPipe – Hand landmark detection
- OpenCV – Webcam input and image processing
- TensorFlow/Keras – Deep learning model development
- LSTM – Sequential hand gesture classification
- Jupyter Notebook – Development and experimentation

Key Features

- Real-time hand tracking using a webcam.
- Extraction of 21 hand landmarks per frame.
- LSTM-based recognition of hand movement sequences.
- Displays the corresponding message for recognized gestures.
- Supports six predefined communication gestures.

How It Works

1. The webcam captures live video.
2. MediaPipe detects the hand and extracts its landmarks.
3. Landmark coordinates are processed into sequences.
4. The trained LSTM model predicts the gesture.
5. The system displays the corresponding message on the screen.

Model Performance

The trained LSTM model achieved 91.67% test accuracy on the current dataset. Performance may vary depending on lighting, hand positioning, and gesture execution.

Future Enhancements

- Add more gestures and communication messages.
- Expand the training dataset.
- Improve recognition accuracy under different conditions.
- Develop a user-friendly graphical interface.
- Explore speech output as an optional future feature.

Project Status

Completed prototype with real-time webcam-based hand gesture recognition and on-screen message display.
