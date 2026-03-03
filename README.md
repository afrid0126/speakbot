🎙️ Speak Bot – Python Voice Assistant

Speak Bot is a desktop voice assistant built using Python that can perform various tasks such as opening applications, searching Wikipedia, sending emails, telling time, fetching news, checking weather, and more — all using voice commands.

🚀 Features

🎤 Voice recognition using SpeechRecognition

🔊 Text-to-speech using pyttsx4

🌐 Open websites (YouTube, Google, W3Schools)

📖 Wikipedia search

📧 Send Emails

📰 Fetch News Headlines

🌦 Get Weather Updates

📱 Send SMS using Twilio

📝 Write & Read Notes

💻 Open system applications

🔒 Lock / Shutdown / Restart system

📷 Capture image using webcam

😂 Tell jokes

🧮 Perform calculations using WolframAlpha

🛠️ Technologies Used

Python 3.x

speech_recognition

pyttsx4

wikipedia

wolframalpha

requests

smtplib

twilio

tkinter

BeautifulSoup

pyjokes

and more...

📦 Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/speak-bot.git
cd speak-bot
2️⃣ Install Required Packages
pip install -r requirements.txt

If requirements.txt is not available, install manually:

pip install pyttsx4 SpeechRecognition wikipedia wolframalpha requests pyjokes twilio ecapture beautifulsoup4 pyaudio
🔑 API Keys Required

To enable full functionality, you must add your API keys:

WolframAlpha API ID

OpenWeather API Key

News API Key

Twilio Account SID & Auth Token

⚠️ Important:
Never hardcode API keys inside the code.
Use environment variables instead.

Example (Windows):

set EMAIL=your_email@gmail.com
set EMAIL_PASSWORD=your_password
▶️ How to Run
python voice_assistant.py

After running:

The assistant will greet you.

Speak your command clearly.

It will execute the task.

Example commands:

"Open YouTube"

"Search Wikipedia for Artificial Intelligence"

"What is the time"

"Send a mail"

"Play music"

"Tell me a joke"

"Shutdown system"

🧠 Project Structure
speak-bot/
│
├── voice_assistant.py
├── speakbot.txt
├── requirements.txt
└── README.md
🔒 Security Improvements Recommended

Remove hardcoded passwords

Use environment variables

Add proper exception handling

Use logging instead of print statements

📌 Future Improvements

Add GUI interface

Add wake word detection

Add ChatGPT integration

Convert to .exe using PyInstaller

Add database for storing commands

Improve NLP for better command understanding

👨‍💻 Author

Created as a Minor Project by CME 2nd Batch Students.
