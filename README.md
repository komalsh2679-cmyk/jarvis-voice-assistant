# Jarvis Virtual Assistant (Python Project)

This is a voice-based virtual assistant named **Jarvis** built using Python. It can perform basic automation tasks like searching Wikipedia, opening websites, telling the time, playing music, and sending emails.

## 🎯 Features

- 🗣️ Speech recognition and voice replies
- 📚 Search and summarize from Wikipedia
- 🌐 Open commonly used websites (YouTube, Google, StackOverflow)
- 🎵 Play music from a specified directory
- 🕒 Tell the current time
- 📧 Send emails via Gmail
- 🧠 Greets the user based on the time of day

## 💻 Technologies Used

- `pyttsx3` – Text-to-speech conversion
- `SpeechRecognition` – Convert speech to text
- `wikipedia` – Retrieve summaries
- `webbrowser` – Open websites
- `datetime` – Time-related features
- `os` – File system interaction
- `smtplib` – Send emails using Gmail

## 🚀 How to Run the Project

1. **Install Python 3.x** if not already installed.

2. **Install Required Libraries**:
   pip install pyttsx3 SpeechRecognition wikipedia

 
Run this in your terminal or command prompt:

python JarvisVirtualAssistant.py


Follow Prompts:

Speak your commands when prompted.

Example commands:

“Wikipedia Albert Einstein”

“Open YouTube”

“Play music”

“What is the time”

“Send email to Harry”

📂 Customization
🔊 Music Folder: You can specify your music folder path when prompted (or leave blank to skip).

📨 Email Credentials: You'll be asked to add your Gmail ID and password directly into the script if environment variables are not used.

⚠️ Note: For the email feature to work securely, it's recommended to use Gmail App Passwords.

🙋‍♀️ Created By
Komal Sharma
A personal project to explore Python speech recognition, automation, and voice interfaces.
