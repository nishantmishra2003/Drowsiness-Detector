# Drowsiness-Detector
Overview

The Drowsiness Detector is a machine learning-based application designed to enhance road safety by detecting signs of driver fatigue in real-time. Using advanced computer vision and deep learning techniques, this system identifies whether a driver is drowsy and provides alerts to prevent accidents.

Features

>Real-time Monitoring: Captures live video feed and analyzes facial landmarks to detect drowsiness.

>Eye Aspect Ratio (EAR) Analysis: Tracks eye closure and calculates EAR to determine alertness levels.

>Audio Alerts: Provides immediate sound notifications when drowsiness is detected.

>Modular Design: Easily adaptable for other use cases like employee monitoring or student attentiveness.

Technologies Used

>Languages: Python

>Libraries/Frameworks:

>OpenCV: For real-time video processing

>PyTorch: For deep learning and model integration

>dlib: For facial landmark detection

>NumPy: For numerical computations

Dataset

The model was trained using datasets of labeled images with awake and drowsy classes, annotated using the LabelMe tool. The YOLOv5 architecture was utilized for object detection.

Installation

Clone the repository:git clone https://github.com/nishantmishra2003/Drowsiness-Detector.git
Navigate to the project directory:cd Drowsiness-Detector
Install the required dependencies:pip install -r requirements.txt

Working Principle

>Preprocessing: Captures the video feed and extracts frames.

>Facial Landmark Detection: Identifies key facial landmarks like eyes, mouth, and head position.

>EAR Calculation: Computes the Eye Aspect Ratio (EAR) to determine if the eyes are closed.

>Alert System: Triggers an alert if the EAR remains below the threshold for a specified duration.

Contributing:

Contributions are welcome! Feel free to open issues or submit pull requests.

License:

This project is licensed under the MIT License. See the LICENSE file for details.
