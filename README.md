# SilentScribe

SilentScribe is a deep learning model inspired by LipNet for lipreading.It can transcribe speech solely based on visual information from lip movements.
The dataset I used: https://spandh.dcs.shef.ac.uk//gridcorpus/

## Description

The SilentScribe employs a Convolutional Neural Network (CNN) architecture combined with Long Short-Term Memory (LSTM) networks. It is trained on datasets of video sequences paired with corresponding transcripts.

The goal of this project is to provide an interactive application that demonstrates the LipNet model. It allows users to select a video and observe the lip movements, as well as view the model's predictions at the token and word level.

## Features

- Video selection: Users can choose a video from the provided options.
- Lip movements visualization: The selected video is displayed, highlighting the lip movements.
- Token-level predictions: The model's predictions are shown as tokens, representing the individual characters or phonemes.
- Word-level predictions: The model's predictions are converted into words for easier interpretation.
- User-friendly interface: The application is built using Streamlit, providing an intuitive and interactive user experience.

Access the application in your browser at: https://chrisdavidson7-silentscribe-appstreamlitapp-b63yi5.streamlit.app/
