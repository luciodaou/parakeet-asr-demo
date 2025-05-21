# Parakeet ASR Demo

Speech recognition using NVIDIA's Parakeet TDT model.

## Features

- 🎙️ Speech-to-text transcription using NVIDIA Parakeet TDT model
- 📊 Real-time transcription with progress tracking
- 📝 Support for multiple audio formats (WAV, FLAC)
- 📈 Transcription history with export options
- 🎯 Optimized for both short and long audio files
- 💻 GPU acceleration support with fallback to CPU

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
streamlit run app.py
```

## Requirements

- Python 3.8+
- NVIDIA GPU with CUDA support (strongly recommended for optimal performance)
- FFmpeg (for audio processing)

## Usage

1. Upload an audio file or record directly in the browser
2. Wait for the model to process and transcribe
3. View and export transcription results

## Notes

- NVIDIA GPU with CUDA support is strongly recommended for optimal performance
- Long audio files (>8 minutes) will automatically use optimized settings
- Maximum recommended audio duration is 30 minutes 