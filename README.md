# 📧 Email Bot with Voice Input

Send emails just by speaking — no typing needed!  
This Python project uses voice commands to help you compose and send emails hands-free using speech recognition and text-to-speech.

---

## 🎯 Features

- 🎙 Voice-controlled email composition  
- 📬 Custom recipient shortcuts  
- 🗣 Text-to-speech prompts for interaction  
- 🚀 Instant email sending via voice

---

## 🛠 Tech Stack

- `SpeechRecognition` – Voice input  
- `pyttsx3` – Text-to-speech feedback  
- `smtplib` – Sending emails through Gmail  
- `PyAudio` – Microphone support

---

## 📦 Installation

Install required packages:

```bash
pip install SpeechRecognition pyttsx3 PyAudio
```

⚠️ If `PyAudio` gives an error:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## ⚙️ Setup Instructions

1. Enable “Less Secure App Access” in your Gmail settings  
👉 [Google Account Security](https://myaccount.google.com/security)

2. In your code, update:

```python
email = 'youremail@gmail.com'
password = 'yourpassword'
```

🔐 For better security, consider using [Gmail App Passwords](https://support.google.com/accounts/answer/185833?hl=en) or OAuth2.

---

## 🚀 How to Use

1. Run the script:

```bash
python main.py
```

2. Speak when prompted:
   - Bot: “What is the subject?”
   - You: “Meeting reminder”
   - Bot: “What should I say in the email?”
   - You: “Don't forget our call at 3 PM.”

✅ Email is sent!

---

## 👥 Contributors

- [@rudrathorat](https://github.com/rudrathorat)  
- [@rudrakshi28](https://github.com/rudrakshi28)

---

## 📬 Contact

Feel free to fork, improve, or reach out for collaboration.  
Let’s make voice automation smarter!
