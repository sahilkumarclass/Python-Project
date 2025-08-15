Ankit A.I - Python Voice Assistant
Ankit A.I is a Python-based voice assistant that listens to user commands, interacts with OpenAI's GPT-3 language model for chat responses, and performs basic tasks like opening websites, playing music, telling the time, and launching applications.

Features
Converts voice input to text using Speech Recognition.

Uses OpenAI GPT-3 (text-davinci-003) for conversational AI capabilities.

Opens popular websites like YouTube, Google, and Wikipedia on command.

Plays the Music app and FaceTime on macOS.

Reports current time.

Saves OpenAI prompt responses to text files.

Voice feedback using system speech synthesis.

Reset chat history and exit commands.

Requirements
Python 3.x

Required Python libraries:

speech_recognition

openai

An OpenAI API key (place it in config.py as apikey)

Installation
Clone this repository.

Install required packages:

bash
pip install speechrecognition openai
Create a config.py file in the project directory with your OpenAI API key:

python
apikey = "your_openai_api_key_here"
(Optional) You may need PyAudio or an alternative library for microphone input. On macOS:

bash
brew install portaudio
pip install pyaudio
Usage
Run the assistant by executing the main script:

bash
python your_script_name.py
Speak commands for:

Opening websites (YouTube, Google, Wikipedia)

Playing music app (open music)

Getting the current time (the time)

Opening FaceTime (open facetime)

Opening Passky app (open pass)

Using AI for custom prompts (using artificial intelligence)

Chatting with the AI assistant

Resetting chat history (reset chat)

Quitting the assistant (Jarvis quit)


Notes
This project is designed for macOS (uses say command for speech and open command for apps).

Modify paths for other operating systems.

Install dependencies and configure API keys before running.

