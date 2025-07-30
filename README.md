# 🎙️ YouTube Transcription with Whisper + yt-dlp

This project enables automatic transcription of YouTube videos using [OpenAI Whisper](https://github.com/openai/whisper) and `yt-dlp` for audio extraction. Built as a simple and efficient tool for downloading and transcribing YouTube audio content into readable text, optionally with timestamps.

## 🔗 Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaryapandya12/youtube-transcription/blob/main/transcription.ipynb)

---

## 📌 Features

- 🎧 Downloads only the audio from any public YouTube video
- 📝 Transcribes audio using Whisper (supports multiple languages)
- ⏱️ Optionally includes timestamps in the transcript
- 💾 Saves output to a `.txt` file (optional)

---

## ⚙️ Requirements

Install the following dependencies in your Colab or local environment:

```bash
pip install yt-dlp openai-whisper
