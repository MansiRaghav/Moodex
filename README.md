# Real-Time Emotion Detection Model

This repository contains a real-time emotion detection system using TensorFlow and OpenCV. The model leverages a Convolutional Neural Network (CNN) to classify emotions from facial expressions in video frames.

## Overview

The project includes two main components:

1. **Emotion Detection Model**: A CNN trained to recognize facial expressions from the [Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset) available on Kaggle.
2. **Real-Time Emotion Detection Application**: A script to capture video from the webcam, detect faces, and classify emotions in real-time.

## Requirements

- Python 3.x
- TensorFlow
- OpenCV
- Keras
- NumPy
- pandas
- scikit-learn
- tqdm
- seaborn
- Matplotlib

## Installation

To install the necessary packages, you can use pip:

```bash
pip install tensorflow opencv-python keras numpy pandas scikit-learn tqdm seaborn matplotlib
```

## Usage

### Method 1: Directly Run the Real-Time Detection

1. Download the `emotiondetector_model.h5` file.
2. Run the `sentiment-analysis-CV.ipynb` file (ensure the file paths in the script match your local setup).

### Method 2: Train the Model Yourself

1. Run the `sentiment-analysis-tfmodel.ipynb` file (preferably on a GPU) to train the model. You can modify the hyperparameters as needed.
2. Save the model as an `.h5` file.
3. Run the `sentiment-analysis-CV.ipynb` file using the model you just trained.

Ensure that the `haarcascade_frontalface_default.xml` file is correctly referenced in the script for face detection.

## File Structure

- `emotiondetector_model.h5`: The trained model file.
- `haarcascade_frontalface_default.xml`: Haar Cascade file for face detection.
- `sentiment-analysis-CV.ipynb`: Script for real-time emotion detection using the webcam.
- `sentiment-analysis-tfmodel.ipynb`: Script for training the emotion detection model.

## Acknowledgement

- [Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset) for providing the dataset.
- [OpenCV](https://opencv.org/) and [TensorFlow](https://www.tensorflow.org/) for their powerful libraries.











