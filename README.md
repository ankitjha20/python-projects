🧠 System Voice Assistant (Python AI Assistant)

A simple yet powerful desktop voice assistant built with Python.
It can recognize your speech, respond using text-to-speech, tell jokes, search Wikipedia, open websites, play music, tell the time, and even send emails — all using your voice commands.

🚀 Features

✅ Speech Recognition – Understands your voice commands using speech_recognition
✅ Text-to-Speech (TTS) – Replies using a natural voice via pyttsx3
✅ Wikipedia Integration – Fetches quick summaries for your queries
✅ Web Automation – Opens YouTube, Google, StackOverflow, and more
✅ System Utilities – Opens applications like Excel, CMD, CodeBlocks, etc.
✅ Entertainment – Tells random programming jokes using pyjokes
✅ Email Sending – Sends emails via Gmail SMTP

🛠️ Requirements
Python Version

Python 3.8 or above is recommended

Install Dependencies

Run the following command inside your virtual environment:

pip install pyttsx3 speechRecognition wikipedia pyjokes


Optionally, if you face issues with audio or microphone:

pip install pyaudio


⚠️ Note (Linux/Mac users):
pyaudio may require additional system dependencies.
For Ubuntu/Debian:

sudo apt-get install portaudio19-dev
pip install pyaudio


Update Email Credentials
In the sendEmail function of main.py, replace:

server.login('youremail@gmail.com', 'your-password')


with your email credentials or preferably use App Passwords for Gmail.

Run the Assistant

python main.py

🗣️ Example Voice Commands
Command	Action
“Wikipedia Albert Einstein”	Reads a short summary about Einstein
“Open YouTube”	Opens YouTube in your browser
“Play Music”	Plays music from your default directory
“Tell me a joke”	Speaks a random programming joke
“What’s the time?”	Tells the current system time
“Email to Manuj”	Sends an email to a predefined address
🧩 Troubleshooting

No speech detected: Check your microphone permissions or adjust r.pause_threshold / timeout values.

Text-to-speech not working: Ensure your system audio output is active.

Email not sent: Enable “Less secure apps” or use Gmail App Passwords
.

🧑‍💻 Tech Stack

Language: Python 🐍

Libraries: pyttsx3, speech_recognition, wikipedia, pyjokes, smtplib, webbrowser, datetime, os

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a PR or raise an issue.

📝 License

This project is licensed under the MIT License
.

❤️ Acknowledgements

Pyttsx3 Documentation

SpeechRecognition Library

Wikipedia API for Python

PyJokes
