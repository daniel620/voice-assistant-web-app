# Voice Assistant Web App
A web application that provides voice assistant capabilities, including speech-to-text (STT), text-to-speech (TTS), and interaction with a large language model (LLM).

This web application is **ready-to-run** once you specify `ENV OPENAI_API_KEY=<your_openai_api_key>` in the Dockerfile. 


## Components Used

- **Language Model**: [OpenAI GPT-3.5-turbo](https://www.openai.com/research/gpt-3)
- **Speech to Text**: [IBM Watson Speech to Text](https://www.ibm.com/cloud/watson-speech-to-text)
- **Text to Speech**: [IBM Watson Text to Speech](https://www.ibm.com/cloud/watson-text-to-speech)
- **Backend Framework**: [Flask](https://flask.palletsprojects.com/)
- **Frontend**: HTML, CSS, JavaScript


## Using Docker

1. Build the Docker image:
    ```bash
    docker build -t voice-assistant-web-app 
    ```
2. Run the Docker container:
    ```bash
    docker run -p 5000:5000 voice-assistant-web-app
    ```
3. Open your web browser and go to `http://localhost:5000`.

## Features

### 1. Select a Voice
![Select Voice](https://github.com/daniel620/voice-assistant-web-app/assets/60392737/72d64bde-e57f-4f0b-8172-e47b781d80e7)

### 2. Record Voice Message
![Record Voice Message](https://github.com/daniel620/voice-assistant-web-app/assets/60392737/2940d17c-b78d-4efb-b148-da48d31ab536)

### 3. Speech to Text
![Speech to Text](https://github.com/daniel620/voice-assistant-web-app/assets/60392737/294ca5cd-72a8-4dbb-916e-cb3e7f264271)

### 4. Communicate with LLM
![Communicate with LLM](https://github.com/daniel620/voice-assistant-web-app/assets/60392737/5d91a494-f23b-43cc-8245-d4e85a809720)

### 5. Text to Speech
![Text to Speech](https://github.com/daniel620/voice-assistant-web-app/assets/60392737/3292619a-adb2-4f8e-b878-e3b2941db968)

### 6. Dark Mode
![Dark Mode](https://github.com/daniel620/voice-assistant-web-app/assets/60392737/591fb9d6-e78b-4b88-86ea-bc26772cc22d)
