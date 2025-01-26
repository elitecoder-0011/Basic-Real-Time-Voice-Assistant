# Real-time Speech-to-Text and Response System

## Objective
The main aim of the project is to develop a basic real-time voice assistant that captures audio input, converts speech to text using OpenAI's Whisper model, generates responses using BlenderBot and converts text to speech using gTTS.
The project uses Hugging Face Transformers (HFT) API to integrate the Whisper model and the BlenderBot.

## Features
- **Audio Recording**: Captures audio input in real-time using `sounddevice` module.
- **Speech-to-Text**: Converts recorded speech into text using the (`openai/whisper-small`) model.
- **Conversational Response**: Generates a response for the transcribed text using BlenderBot (`facebook/blenderbot-400M-distill`).
- **Text-to-Speech**: Converts the response to speech using gTTS(`Google Text to Speech`)
- **Flask Integration**: Supports a basic web interface for user interaction.

---

## Requirements
- Python 3.8+
- Internet connection (to run Hugging Face models)

---

## Setup Steps

1. Download the python file(`project.ipynb`) and the `requirements.txt` file from the repository into your system.
2. Install the required libraries and dependencies for the project by referring to the `requirements.txt` file.
3. Run the python file.

---

## Usage Guide

### 1. Install Necessary Packages and Import Necessary Modules
- Install all the necessary packages required for the project. 
- Import all the necessary modules to run the python code.

### 2. Record Audio
- Run the corresponding cell to start recording the audio.
- Press any key to stop the recording.
- The recorded audio will be saved as `audio_record.wav`.

### 3. Transcribe Audio
- Run the corresponding cell to transcribe audio.
- The transcribed text will be displayed in the output of the respective cell.

### 4. Generate a Response
- Run the corresponding cell to generate a response for the transcribed text.
- The transcribed text will be given as input to the BlenderBot. The bot will generate and display a response.

### 5. Convert Response to Speech
- Run the corresponding cell to convert the bot's response to speech.
- The bot's response will be converted to speech using gTTS(Google Text to Speech).
- The converted audio will be played using playsound module.
- The converted audio will be saved as `audio_response.mp3`.

### 6. Web Interface
- Run the corresponding cell to create a basic web interface using Flask.
- The web link will be displayed in the output cell.
- Click on the web link to view the contents of the web interface.


---


