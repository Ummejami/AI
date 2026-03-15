# Speech Emotion Recognition Using Deep Learning

## Overview
Speech Emotion Recognition (SER) is the task of identifying human emotions from speech signals. In this project, audio data is processed, important speech features are extracted, and a classification model is trained to detect emotions from voice recordings.

## Objective
The main objective of this project is to build a model that can recognize emotions from speech audio accurately and efficiently.

## Features
- Audio preprocessing
- Feature extraction from speech signals
- Emotion classification
- Model training and evaluation
- Prediction on new audio samples

## Dataset
This project uses a speech emotion dataset containing labeled audio samples for different emotions. I used Ravdess Dataset.
Download link 
```bash
https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio
```

Example emotions:
- Angry
- Happy
- Sad
- Neutral
- Fearful
- Disgust
- Surprised

## Technologies Used
- Python
- Jupyter Notebook / Google Colab
- NumPy
- Pandas
- Librosa
- Matplotlib
- Scikit-learn
- TensorFlow / Keras / PyTorch

## Project Workflow
1. Load the speech emotion dataset
2. Preprocess audio files
3. Extract audio features such as MFCC, Chroma, and Mel Spectrogram
4. Split dataset into training and testing sets
5. Train the classification model
6. Evaluate model performance
7. Predict emotions from unseen speech samples

## Audio Features Used
The following audio features were extracted:
- MFCC (Mel Frequency Cepstral Coefficients)
- Chroma Features
- Mel Spectrogram
- Zero Crossing Rate
- RMS Energy

## Model
The model was trained to classify emotions from extracted speech features.

Example models:
- CNN
- LSTM
- ANN
- SVM
- Random Forest

## Evaluation
The model was evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report

## Results
The trained model was able to classify speech emotions with satisfactory performance on the test dataset.
CNN+LSTM performed best for my feature.

## Project Structure

```bash
Speech-Emotion-Recognition/
│── dataset/
│   ├── features.csv
│   ├── mel_spectrogram_features.csv
│   ├── mfcc_features.csv
│   └── noisy_stretched_features.csv
│
│── models/
│   ├── CNN+LSTM.ipynb
│   └── speech.ipynb
│
└── README.md
```
