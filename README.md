# AP-LANGUAGE-IDENTIFICATION

## Problem Statement
Identifying the language of spoken content is important in a multilingual world for a variety of applications such as transcription services, content categorization, and more. This is an attempt to create an application that can recognize four different spoken Indian languages from audio extracted from YouTube videos (multi-class classification). The audio samples in the dataset are from four different Indian languages. Each audio sample is 5 seconds long. This dataset was created using regional YouTube videos. The dataset includes the following languages: Hindi, Kannada, Tamil, and Telugu.

## Proposed Solution

A custom CNN model to identify the spoken language from audio using the following steps:
1. Prep-process the data: Resampling, adjusting the number of channels, padding data if necessary
2. Convert the pre-processed data into a Mel Spectrogram image
3. Build a custom CNN model and train on a custom dataset created using Mel Spectrogram images
4. Create a web app
5. Deploy on the cloud

Refer flowchart folder for more details

## To run the code:
1. **Setup**: Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the Application**: Execute the main application file:
   ```bash
   python app.py
   ```
## Resources used:
* Deep Learning Framework - PyTorch & Torchaudio
* Web Framework - Flask application that takes in audio and recognizes the language from that audio
* Cloud Platform - Google Cloud Platform
