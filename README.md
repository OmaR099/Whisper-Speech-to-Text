# Speech-to-Text Using OpenAI Whisper Model  

This project implements a Speech-to-Text (STT) system utilizing OpenAI's Whisper model for converting audio speech into text. The project supports multiple models to cater to performance and resource requirements: Large v3, Medium, Small, Turbo, Base, and Tiny.   

Additionally, it features a user-friendly interface using Gradio, allowing users to test the model by either uploading audio files or recording audio directly through a microphone. The system supports many languages but focuses on English and Arabic audio inputs.

## Table of Contents  

- [Features](#features)  
- [Models](#models)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Demo](#demo)  
- [Contributing](#contributing)  
- [License](#license)  
- [Acknowledgements](#acknowledgements)  

## Features  

- **Multiple Models**: Choose from Whisper models (Large, Medium, Small, Turbo, Base, Tiny) based on your performance requirements and available hardware.  
- **Multi-language Support**: Supports speech-to-text conversion for both English and Arabic languages.  
- **User-Friendly Interface**: Testing made easy through a Gradio interface for audio uploads or microphone recording.  
- **Real-time Transcription**: Instant transcription of audio input into text.  

## Models  

The following Whisper models are implemented in this project:  

- **Large v3**: High accuracy with more resource requirements.  
- **Medium**: Balanced performance and resource utilization.  
- **Small**: Lightweight model for faster execution with reasonable accuracy.  
- **Turbo**: Optimized for speed, trading off some accuracy.  
- **Base**: Low resource requirements for simple applications.  
- **Tiny**: Minimal performance requirements for very constrained environments.  

## Installation  

To set up this project, follow these instructions:  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/speech-to-text-whisper.git  
   cd speech-to-text-whisper
