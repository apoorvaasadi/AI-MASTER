AI-Master 

AI-Master is a Python-based AI voice assistant that uses speech recognition and text-to-speech technology to understand user voice commands and perform various tasks automatically. The assistant can open websites, search information, tell the current time and date, and execute system commands.

This project demonstrates basic concepts of Artificial Intelligence, Natural Language Processing (NLP), and automation using Python.

Features

Voice command recognition

Text-to-speech response

Open websites (YouTube, Google, Gmail, etc.)

Search information from Wikipedia

Tell current time and date

Open system applications (Notepad, Calculator, Command Prompt)

Play music

Tell jokes and random facts

System commands like shutdown and restart

Technologies Used

Python

SpeechRecognition

Pyttsx3

Wikipedia API

Webbrowser

OS module

Installation

Install the required libraries using pip:

pip install SpeechRecognition
pip install pyttsx3
pip install wikipedia
pip install pyaudio

If PyAudio installation fails, run:

pip install pipwin
pipwin install pyaudio
How to Run

Navigate to the project folder and run:

python assistant.py

The assistant will start listening for voice commands.

Example Commands

You can say commands like:

open youtube

open google

search machine learning

wikipedia python

tell me the time

tell me a joke

open calculator

open notepad

shutdown computer

exit

Project Structure
AI-Master
│
├── assistant.py
└── README.md
Future Improvements

Add wake word detection (Hey Jarvis)

Integrate ChatGPT for conversational AI

Add graphical user interface (GUI)

Add more automation features
