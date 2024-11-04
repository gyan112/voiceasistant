Sudha - Nepali Voice Assistant
voice-assistant

Sudha is a Nepali Voice Assistant built using Python. It can perform various tasks such as opening websites, playing songs, getting the current time and date, sending emails, checking the weather, and more.

Features
Voice Recognition: Sudha uses the SpeechRecognition library to recognize voice commands.
Text-to-Speech: Pyttsx3 is employed for converting text responses to speech.
Task Execution: The assistant can perform tasks based on user commands, such as opening websites, playing songs, and more.
Email Functionality: Sudha can send emails with a specified recipient, subject, and body.
Weather Information: Get real-time weather updates for a specific city using the OpenWeatherMap API. Greetings: Sudha greets you based on the time of the day.
Configure the assistant:
Set your Gmail credentials in the send_email function.
Replace 'your_openweathermap_api_key' with your OpenWeatherMap API key.
Usage
Greetings: Sudha greets you based on the time of the day.
Commands: Speak commands such as:
Hello
Open YouTube
Play a song
Get the time
Send an email
Check the weather
Exit: Say "Exit" or "Bye" to end the interaction with Sudha.
Prerequisites
Before running the program, ensure you have the required Python libraries installed. You can install them using the following commands:

pip install pyttsx3
pip install SpeechRecognition
pip install datetime
pip install pyowm
pip install webbrowser
