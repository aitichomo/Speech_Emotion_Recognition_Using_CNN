# Speech Emotion Recognition Using CNN with the RAVDESS Dataset

## Overview

This project implements a Convolutional Neural Network (CNN) for emotion classification in speech using the RAVDESS dataset. The goal is to accurately recognize emotions such as happy, sad, angry, fearful, disgusted, surprised, and neutral from audio recordings. This can be applied in various fields like human-computer interaction, mental health monitoring, and customer service automation.

## Dataset

- **Source**: [RAVDESS Dataset](https://zenodo.org/record/1188976)
- **Contents**: 24 actors (12 male, 12 female) performing 7 emotions (calm, happy, sad, angry, fearful, disgusted, surprised) and a neutral utterance. Each emotion is represented by 24 audio files.

## Features

- **Data Preprocessing**: Audio file loading, Mel-Frequency Cepstral Coefficients (MFCCs) extraction, and data augmentation.
- **Model Architecture**: Custom CNN model with convolutional layers, pooling layers, and dense layers.
- **Training & Evaluation**: Utilizes Keras with TensorFlow backend, includes early stopping, learning rate scheduling, and evaluation metrics such as accuracy, precision, recall, and F1-score.



