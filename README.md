# YouTube Video Summarizer

The **YouTube Video Summarizer** is a Python-based tool that automatically summarizes YouTube videos. By leveraging Natural Language Processing (NLP) techniques, this tool extracts key points from video transcriptions, providing you with concise and informative summaries of video content. Whether for research, time-saving, or content review, the tool helps you quickly grasp the main points of any YouTube video.

## Features

- **Automatic Video Transcription**: Extracts the audio from YouTube videos and transcribes it into text.
- **Text Summarization**: Uses NLP models to summarize long transcriptions into shorter, meaningful summaries.
- **Easy-to-Use Interface**: Simple setup with minimal configuration required.

## Technologies Used

- **Python**: The primary programming language used for the development of this tool.
- **YouTube API**: To fetch video details and audio for transcription.
- **Transformers**: To perform text summarization using advanced models like BERT.
- **Speech-to-Text**: Converts audio from YouTube videos to text.

## How It Works

1. **Input**: Provide a YouTube video URL or ID.
2. **Transcription**: The tool fetches the audio and transcribes it into text.
3. **Summarization**: The transcribed text is processed and summarized into concise content.
4. **Output**: The summarized text is displayed to the user or can be exported as a text file.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- pip (Python's package installer)

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/DiabolikArms/yt_video_summariser.git
   cd yt_video_summariser
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

## Usage

To use the YouTube Video Summarizer, simply run the app and input the YouTube video URL. The tool will handle the rest—fetching the video, transcribing the audio, and providing a summary.
