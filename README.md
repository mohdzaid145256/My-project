Smart Mood Detection

Overview

Smart Mood Detection is a real-time facial emotion recognition system that leverages deep learning techniques to analyze human emotions such as happiness, sorrow, anger, and surprise. This project employs Convolutional Neural Networks (CNNs) to enhance recognition accuracy and improve real-world adaptability.

This work has been accepted and published by IEEE, reinforcing its credibility and contribution to the field of human-computer interaction and artificial intelligence.

Features

Real-Time Mood Detection: Uses a webcam feed to detect and classify emotions instantly.

Preprocessing Pipeline: Applies grayscale conversion, scaling, normalization, and augmentation techniques.

Deep Learning-based Approach: Utilizes CNNs optimized for speed and accuracy.

Robust Performance: Achieves 99% accuracy on the FER-2013 dataset.

Applications: Useful in security surveillance, healthcare, human-computer interaction, mental health monitoring, and customer sentiment analysis.

Technologies Used

Programming Language: Python

Deep Learning Frameworks: TensorFlow, Keras

Computer Vision Library: OpenCV

Dataset: FER-2013 (Facial Emotion Recognition dataset)

System Architecture

Video Frame Capture: Webcam feed captures real-time facial images.

Preprocessing: Frames undergo grayscale conversion, resizing, and normalization.

Face Detection: A Haar cascade algorithm isolates the face.

Feature Extraction: CNNs extract relevant facial patterns.

Emotion Classification: The processed features are classified into predefined mood categories (Neutral, Happy, Sad, Angry, Surprise, etc.).

Live Feedback: The identified emotion is displayed in real-time.

Installation

To run this project locally, follow these steps:

Prerequisites

Python 3.x

pip (Python package manager)

A working webcam

Setup

Clone this repository:

git clone https://github.com/your-username/smart-mood-detection.git
cd smart-mood-detection

Install required dependencies:

pip install -r requirements.txt

Run the application:

python main.py

Dataset

This project uses the FER-2013 dataset, which contains 35,887 grayscale images (48x48 pixels) across seven emotion categories:

Angry

Disgust

Fear

Happy

Sad

Surprise

Neutral



