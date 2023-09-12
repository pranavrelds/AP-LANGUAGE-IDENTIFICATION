# AP-LANGUAGE-IDENTIFICATION

## Problem Statement
In a multilingual world, identifying the language of spoken content is essential for various applications, including transcription services, content categorization, and more. Manual identification is not scalable and can be error-prone. This project provides a solution for an automated and efficient recognition of spoken languages from audio clips.

## Solution
The AP-LANGUAGE-IDENTIFICATION project provides a solution for recognizing languages from spoken content. The application is built using Flask and offers a user-friendly interface where users can upload audio clips and get the identified language.

- **Training**: The application has a training pipeline in place, which can be triggered via the `/train` endpoint. This pipeline is designed to train a model on a dataset of audio clips and their corresponding languages.

- **Prediction**: The `/predict` endpoint allows users to input an audio clip and receive the identified language.

## How to Run the Code

1. **Setup**: Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the Application**: Execute the main application file:
   ```bash
   python app.py
   ```
## Resources used:
Framework - PyTorch & Torchaudio
Web Framework - Flask application that takes in audio and recognizes the language from that audio
Cloud Platform - Google Cloud Platform
