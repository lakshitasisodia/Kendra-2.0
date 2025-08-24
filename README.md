
---

# 🎙️ Kendra 2.0 - Voice Assistant

**Kendra** is a lightweight voice-controlled assistant built with Python. It can perform basic web browsing tasks, answer simple math queries, and communicate with the user through text-to-speech interaction.

> ⚠️ This is a **private repository** intended for personal or educational use.

---

## 🧠 Features

* 🎧 Listens for a wake word: **"Kendra"**
* 🌐 Opens websites via voice commands (e.g., "open YouTube")
* ➕ Handles basic math operations (e.g., "what is 5 plus 3")
* 💬 Provides help and graceful error handling
* 🗣️ Uses text-to-speech for responses

---

## 🛠️ Tech Stack

* `speech_recognition` – for capturing and interpreting voice input
* `pyttsx3` – for text-to-speech output
* `webbrowser` – to launch URLs
* `re` and `operator` – for processing math expressions

---

## ⚙️ Installation

> Tested on Python 3.8+

1. **Clone the repository**

```bash
git clone https://github.com/your-username/your-private-repo.git
cd your-private-repo
```

2. **Set up your environment**

```bash
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not yet created, generate it using:

```bash
pip freeze > requirements.txt
```

---

## ▶️ How to Run

Simply run the script:

```bash
python kendra.py
```

You'll be greeted and prompted to speak. Use the wake word **"Kendra"** followed by your command.

Examples:

* `Kendra, open google`
* `Kendra, calculate ten divided by two`
* `Kendra, help`
* `Kendra, exit`

---

## 📌 Notes

* Make sure your microphone is enabled and accessible.
* The assistant has a timeout after 5 seconds of silence.
* Wake word detection is done using basic keyword matching (`"kendra"` in recognized speech).

---

## 🔒 Privacy

This assistant processes voice commands locally and does **not** send any data externally. It uses the Google Speech API **only** for speech-to-text transcription.

---

## 🙋‍♀️ Acknowledgments

* Built with ❤️ by **Lakshita**
* Thanks to the open-source Python community

---

