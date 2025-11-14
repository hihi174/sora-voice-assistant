# sora-voice-assistant
Sora Voice Assistant is a Python-based voice-controlled desktop assistant with wake-word activation, speech recognition, and offline text-to-speech. It supports both voice and typed commands, allowing users to search Google, play YouTube videos, and open websites automatically. Built with multithreading and queue-based processing.



# Sora Voice Assistant 🎤

Sora is a custom voice-controlled assistant built in Python.  
It supports wake-word activation, speech recognition, YouTube playback, Google search, and opening websites — all using an offline text-to-speech engine and online speech recognition.

---

## 🚀 Features

- Wake-word detection: “Sora”
- Voice + text command interface
- Text-to-speech (pyttsx3)
- Speech recognition (Google API)
- YouTube search and auto-play
- Google search in browser
- Website opener commands
- Background queue for songs + speech
- Threaded architecture for smooth performance

---

## 🧩 Tech Stack

- Python 3.9+
- speech_recognition
- pyttsx3
- requests
- urllib
- re
- webbrowser
- threading + queues

---

## 📦 Installation

### 1. Clone the repository:
```bash
git clone https://github.com/<your-username>/sora-voice-assistant.git
cd sora-voice-assistant
