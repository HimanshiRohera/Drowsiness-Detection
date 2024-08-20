This project is a drowsiness detection system that uses machine learning and computer vision techniques to monitor the driver's eyes and sound an alarm if drowsiness is detected. The system utilizes a webcam to capture live video, detects facial landmarks, and calculates the eye aspect ratio to determine whether the driver's eyes are closed for an extended period.

Features

Real-time drowsiness detection using a webcam.
Eye aspect ratio calculation to monitor eye closure.
Plays an alarm sound when drowsiness is detected.
Utilizes dlib's facial landmark detector for accurate eye tracking.

Prerequisites

Before running the project, ensure you have the following libraries installed:

- imutils
- dlib
- opencv-python (cv2)
- pygame

Setup

Download the facial landmark predictor:

Download the shape_predictor_68_face_landmarks.dat file from the above link.
Place it in the project directory.

Alarm Sound:

Ensure you have an alarm sound file named alaram.wav in the project directory. You can replace this with any sound of your choice.
