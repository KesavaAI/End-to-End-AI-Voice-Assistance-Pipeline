# End-to-End-AI-Voice-Assistance-Pipeline
This repository contains the implementation of an End-to-End AI Voice Assistance Pipeline designed to convert voice input into meaningful text responses using state-of-the-art AI models. The pipeline is designed to handle tasks such as voice-to-text conversion, natural language processing, and text-to-speech synthesis with tunable parameters.

## Features

- **Voice-to-Text Conversion:** Utilizes Whisper to transcribe spoken words into text.
- **Natural Language Processing:** Employs Large Language Models (LLMs) via Hugging Face Transformers to understand and generate text responses.
- **Text-to-Speech Synthesis:** Converts text back into speech using various models with adjustable pitch, voice gender, and speed.
- **Voice Activity Detection (VAD):** Minimizes latency by detecting and processing active voice segments.
- **Output Restriction:** Limits responses to a maximum of 2 sentences for concise communication.

## Technologies Used

- **Python**: Primary programming language for the pipeline.
- **Whisper**: Used for accurate voice-to-text conversion.
- **Hugging Face Transformers**: Implements the LLM for text understanding and generation.
- **Text-to-Speech Models**: Converts text into natural-sounding speech with configurable parameters.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/voice-assistance-pipeline.git
    ```

## Usage

1. **Voice Input**: Speak into the microphone.
2. **Processing**: The pipeline transcribes the voice input to text, processes it through the LLM, and then converts the response back to speech.
3. **Output**: Hear the AI-generated response.

### Tunable Parameters

- **Pitch**: Adjust the pitch of the synthesized voice.
- **Voice Gender**: Select between male or female voice.
- **Speed**: Control the speed of the speech output.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your improvements.
