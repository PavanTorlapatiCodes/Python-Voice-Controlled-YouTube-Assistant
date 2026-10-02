# 🎙️ Python Voice-Controlled YouTube Assistant

A simple **Python Voice Assistant** that listens to voice commands, processes the command, responds using Text-to-Speech, and automatically plays requested songs on YouTube.

## 🚀 Project Overview

This project demonstrates how Python can be used to build an interactive **voice-driven automation system**.

The assistant listens through the microphone and uses speech recognition to convert spoken commands into text.

The assistant recognizes the wake word **"Mike"** and processes commands such as:

> "Mike play Believer"

The requested song is then automatically opened and played on YouTube.

---

## ✨ Features

* 🎤 Voice command recognition
* 🧠 Wake-word based command processing
* 🔊 Text-to-Speech responses
* ▶️ Automatic YouTube song playback
* 🎧 Microphone-based interaction
* ⚡ Python automation
* 🔗 Integration of multiple Python libraries
* 🛠️ Exception handling for runtime errors

---

## 🧩 Project Workflow

```text
User Voice
    ↓
Microphone Input
    ↓
Speech Recognition
    ↓
Speech → Text
    ↓
Detect "Kodi"
    ↓
Process Command
    ↓
Extract Song Name
    ↓
PyWhatKit
    ↓
YouTube
    ↓
Play Song
    ↓
Text-to-Speech Response
```

---

## 🛠️ Technologies Used

| Technology                | Purpose                   |
| ------------------------- | ------------------------- |
| Python                    | Core programming language |
| SpeechRecognition         | Converts speech into text |
| PyAudio                   | Microphone/audio input    |
| pyttsx3                   | Text-to-Speech            |
| PyWhatKit                 | YouTube automation        |
| Google Speech Recognition | Speech-to-text processing |

---


## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Python-Voice-Assistant.git
```

### 2. Navigate into the project

```bash
cd Python-Voice-Assistant
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python voice_assistant.py
```

The program will start listening through the microphone.

Try saying:

```text
mike play Believer
```

The assistant will recognize the command, respond using Text-to-Speech, and open the requested song on YouTube.

---

## 💻 Example

### Voice Command

```text
mike play Believer
```

### Processing

```text
"mikei play believer"
        ↓
Remove "kodi"
        ↓
"play believer"
        ↓
Extract "believer"
        ↓
YouTube search/play
```

---

## 🧠 Key Concepts Learned

Through this project, I practiced:

* Python functions
* Exception handling
* Microphone input
* Speech-to-text conversion
* Text-to-Speech
* String manipulation
* Voice command processing
* Python automation
* Third-party library integration

---

## 🔮 Future Enhancements

Planned improvements include:

* 🎙️ Continuous listening mode
* 🧠 More natural-language commands
* 🤖 LLM integration
* 🔗 AI Agent integration
* 🌐 Web-based interface using Gradio
* 📋 Multiple command support
* ⏰ Reminders and task automation
* 📧 Email automation
* 🔍 Intelligent web search
* 🗣️ Improved conversational interaction

---

## 👨‍💻 Author

**Pavan Kumar Torlapati**

Python Developer | Generative AI & Agentic AI Enthusiast

GitHub:
https://github.com/PavanTorlapatiCodes

LinkedIn:
https://linkedin.com/in/pavan-torlapati-7543732ba

---

## ⭐ If you find this project useful

Consider giving the repository a ⭐ and exploring the other projects in my GitHub portfolio.
