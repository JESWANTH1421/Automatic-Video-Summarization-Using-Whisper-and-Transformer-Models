# Automatic-Video-Summarization-Using-Whisper-and-Transformer-Models
This project extracts audio from YouTube videos, converts speech to text using OpenAI Whisper, and summarizes the content using transformer-based NLP models to save time and improve content accessibility.
🔹 Project Overview

This project automatically generates concise text summaries from YouTube videos. It extracts audio from videos, converts speech to text using OpenAI Whisper, and summarizes the content using transformer-based NLP models. The system helps users quickly understand long videos without watching them fully.

🚀 Features

Download YouTube videos automatically using yt-dlp

Extract audio from video using FFmpeg and MoviePy

Transcribe speech to text using OpenAI Whisper

Summarize long transcripts using BART (Transformer model)

Save summarized output in text format for easy reading

🧰 Technologies Used

Python – Core programming language

OpenAI Whisper – Speech-to-text transcription

HuggingFace Transformers (BART) – Text summarization

MoviePy & FFmpeg – Audio extraction

yt-dlp – YouTube video download

⚙️ How It Works

Provide a YouTube video URL.

Download the video using yt-dlp.

Extract audio from the video using MoviePy and FFmpeg.

Transcribe the audio into text using OpenAI Whisper.

Summarize the transcript using BART model.

Output both summary.txt and a formatted Markdown output for GitHub.

📁 Project Structure
AI-Video-Summarization/
│
├── video_summarizer.py      # Main Python script
├── input_video.mp4          # Input YouTube video (downloaded)
├── audio.wav                # Extracted audio
├── summary.txt              # Generated summary
├── OUTPUT.md                # Formatted GitHub output
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies

📝 Sample Input & Output

Input: YouTube video about Machine Learning lecture.

Generated Summary:

The video explains the fundamentals of machine learning, including supervised and unsupervised learning, real-world applications, and how data is used to train intelligent systems. It helps viewers understand the topic quickly without watching the full lecture.

💡 Use Cases

Summarize online lectures and tutorials

Generate concise notes from webinars and podcasts

Create study material from long educational videos

Improve accessibility for visually impaired users

📌 Conclusion

The AI-Powered Video Summarization System demonstrates the practical application of AI in extracting, processing, and summarizing video content. It combines speech recognition and transformer-based NLP to provide a time-saving, user-friendly solution for learning and research.
