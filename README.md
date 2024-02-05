# Real-Time Emotion Detection

Real-time emotion detection is a project aimed at developing a system that can accurately detect and interpret human emotions in real-time using advanced technologies such as computer vision and machine learning.

## Setup

1. **Download HAAR-Cascade File**: 
   - Download the HAAR-Cascade file from [here](https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml).

2. **Download Dataset**:
   - The dataset used for training can be downloaded from [Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data).

3. **Installation**:
   - Install the required dependencies by running `pip install -r requirements.txt`.

## Usage

1. **Training the Model**:
   - Run `python main.py` to create and train the model.

2. **Running the UI**:
   - Execute `python UI.py` to implement the face-emotion recognition interface.

## Overview

Emotions are crucial for human communication and behavior. Real-time emotion detection systems leverage technologies like computer vision and machine learning to analyze facial expressions, vocal cues, or physiological signals and classify them into specific emotional states.

## Methodology

This project utilizes Keras (Tensorflow) along with OpenCV and haar-cascade for real-time emotion detection. Keras provides a high-level API for building and training neural networks, making it ideal for this purpose.

## Dataset

The project uses the Facial Emotion Detection (FER) dataset compiled in 2013, available on Kaggle. The dataset consists of grayscale images of faces labeled with seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.

## Result

The trained face-emotion detection model achieves high accuracy in detecting and classifying various emotions from facial expressions, demonstrating the effectiveness of deep learning algorithms in emotion analysis.

By following this guide, you can set up and utilize a real-time emotion detection system for various applications in human-computer interaction, healthcare, marketing, and entertainment.
![Happy](https://github.com/ankita1408/realtime_facial_emotion-/blob/main/Screenshot%202024-02-06%20021125.png)
![Angry](https://github.com/ankita1408/realtime_facial_emotion-/blob/main/Screenshot%202024-02-06%20020521.png)
