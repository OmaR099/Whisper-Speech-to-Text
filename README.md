# Speech-to-Text Using OpenAI Whisper Model  

This project implements a Speech-to-Text (STT) system utilizing OpenAI's Whisper model for converting audio speech into text. The project supports multiple models to cater to performance and resource requirements: **Tiny, Base, Small, Medium, Turbo, and Large v3.**  

Additionally, it features a user-friendly interface using Gradio, allowing users to test the model by either uploading audio files or recording audio directly through a microphone. The system supports many languages but focuses on English and Arabic audio inputs.

## Table of Contents  

- [Features](#features)
- [Models](#models)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features  

- **Multiple Models**: Choose from Whisper models (Tiny, Base, Small, Medium, Turbo, and Large v3) based on your performance requirements and available hardware.  
- **Multi-language Support**: Supports speech-to-text conversion for both English and Arabic languages.  
- **User-Friendly Interface**: Testing is made easy through a Gradio interface for audio uploads or microphone recording.  
- **Real-time Transcription**: Instant transcription of audio input into text.  

## Models  

The following Whisper models are implemented in this project:  

- **Tiny**: Minimal performance requirements for very constrained environments.
- **Base**: Low resource requirements for simple applications.
- **Small**: Lightweight model for faster execution with reasonable accuracy.
- **Medium**: Balanced performance and resource utilization.
- **Turbo**: Optimized version of large-v3 that offers faster transcription speed with minimal degradation in accuracy.
- **Large v3**: High accuracy with more resource requirements.

![image](https://github.com/user-attachments/assets/8d4ae623-bdb3-4f60-ac7d-d7bcd3940139)

## Installation  

To set up this project, follow these instructions:  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/OmaR099/Whisper-Speech-to-Text 
   cd speech-to-text-whisper
   ```
   
2. Create a virtual environment (optional but recommended):
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # For Linux / macOS  
   venv\Scripts\activate     # For Windows
   ```
   
3. Install the required packages:
   ```bash  
   pip install -r requirements.txt
   ```

## Usage

To run the application, execute the following command:
   ```bash  
   python app.py
   ```
This will start a local server. Open the provided URL in your web browser to access the Gradio interface.

**How to Use the Interface**

**Upload Audio:** Click on the upload button to select an audio file in English or Arabic.
**Record Audio:** Use the microphone button to record audio directly from your device.
**Transcribe**: Once the audio is uploaded or recorded, the system will automatically transcribe the speech into text.

## Acknowledgements

- **OpenAI Whisper** for providing a state-of-the-art speech-to-text model.
- **Gradio** for creating an intuitive interface to demo the project.
- Contributors and the open-source community for guidance and support.
