# Async Text-to-Speech: GPT Response with Elevenlabs Voice

## Overview
This project is an asynchronous text-to-speech (TTS) service implemented in Python, utilizing OpenAI's GPT models and ElevenLabs' API for generating spoken audio from text. It is designed to handle real-time text inputs, convert them into natural-sounding speech, and stream the audio back to the user. This service is particularly useful for applications needing interactive voice responses or for integrating advanced speech capabilities into existing Python applications.

### Demo
```
User: python gpt_eleventlabs.py
Assistant: Enter your query or 'exit' to quit:
User: <your question query>
Assistant: Started streaming audio...

Assistant: Enter your query or 'exit' to quit:
User: <your question query>
Assistant: Started streaming audio...
...
```

## Features
- **Real-Time Text Processing**: Converts real-time text input into spoken audio without noticeable delays.
- **High-Quality Voice Synthesis**: Uses ElevenLabs' voice synthesis API for natural-sounding audio output.
- **Asynchronous Operation**: Built with asyncio to handle concurrent audio streaming efficiently.
- **Easy to Use**: Simple command-line interface for sending queries and receiving audio responses.

## Prerequisites
Before you run this project, you need to install several dependencies and have the necessary API keys from OpenAI and ElevenLabs. Ensure you have Python 3.7 or higher installed on your system.

### Dependencies
- `asyncio` for asynchronous programming
- `websockets` for handling WebSocket connections
- `openai` Python client for accessing OpenAI's API
- `subprocess` and `shutil` for local audio playback

### API Keys
- **OpenAI API Key**: Sign up at [OpenAI](https://openai.com/api/) and generate an API key.
- **ElevenLabs API Key**: Obtain an API key by registering at [ElevenLabs](https://www.elevenlabs.io/).

## Setup
1. Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/Tizzzzy/TTS_gpt_elevenlabs.git
   ```
2. Navigate to the cloned directory:
   ```bash
   cd your-repository-name
   ```
3. To start the code, run:
   ```bash
   python gpt_elevenlabs.py
   ```
## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your enhancements. For major changes, please open an issue first to discuss what you would like to change.

If you like this project, please give me a star
