# Audio Message Transcription and Response Generation Project

## Introduction

Minimal implementation for Voice Assistant.

## Installation

### Prerequisites

- Python 3.8 or newer
- Streamlit
- Streamlit Audio Recorder
- Whisper model from OpenAI (for the backend)
- dotenv (for environment variable management)

### Backend Setup

1. Clone the repository to your local machine.
2. Navigate to the project directory and install the Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root of the backend project directory and add your OpenAI API key:

    ```env
    OPENAI_API_KEY=your_api_key_here
    ```

4. Start the STreamlit Application:

    ```bash
    streamlit run main.py
    ```