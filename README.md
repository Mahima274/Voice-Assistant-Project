# Voice Assistant App - Meera

A simple Python-based voice assistant that uses speech recognition and text-to-speech to interact with users. Meera can answer questions, fetch weather updates, open websites, search Wikipedia, tell the time, and schedule reminders.


## Features

- Speech recognition using `speech_recognition` library  
- Text-to-speech using `pyttsx3` with a female voice  
- Search and summarize Wikipedia articles  
- Open websites and YouTube in a browser  
- Fetch current weather information using OpenWeatherMap API  
- Tell current system time  
- Basic scheduling placeholder for reminders  
- Auto-exit after 2 minutes of inactivity  


## Requirements

- Python 3.x  
- Packages:
  - pyttsx3  
  - SpeechRecognition  
  - wikipedia  
  - requests  
  - pyaudio (for microphone input)  

You can install all dependencies with:  
```bash
pip install pyttsx3 SpeechRecognition wikipedia requests pyaudio
Setup
Clone the repository:

git clone https://github.com/Mahima274/Voice-Assistant-Meera.git
Obtain an OpenWeatherMap API key from https://openweathermap.org/api and replace the api_key variable in the script.

Run the assistant script:
python your_script_name.py
How to Use
Run the script and greet Meera by saying "Hello Meera"

Ask for the current time, weather in any city, or search Wikipedia by saying phrases like "Wikipedia [topic]"

Open websites by saying "Open a website" and providing the URL when prompted

Say "YouTube" to open YouTube in the browser

Schedule tasks (basic placeholder functionality) by saying "Schedule"

Say "Goodbye" to exit the assistant

Code Overview
Text-to-speech: pyttsx3 is used to convert text responses to speech

Speech recognition: Uses Google Web Speech API to convert speech input to text

Wikipedia searches: Summarizes topics in 2 sentences

Weather data: Uses OpenWeatherMap API for real-time weather info

Auto-exit: Closes after 2 minutes of inactivity for convenience

Future Improvements
Implement full reminder scheduling with alarms

Add more natural conversation capabilities

Improve error handling and fallback responses

Integrate with calendar and messaging apps
