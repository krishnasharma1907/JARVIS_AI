# 🎙️ JarvisTTS

> Advanced AI Voice Assistant powered by Google Gemini TTS Models

    

---

# ✨ Features

* 🎤 AI Powered Text To Speech
* 🧠 Google Gemini TTS Integration
* 🎧 30 Unique AI Voices
* 🇮🇳 Indian Voice Library
* 🌐 Hindi / English / Hinglish Support
* 🔊 Voice Preview System
* 🕘 Audio History
* ⚡ Fast Audio Generation
* 🎨 Modern Dark UI
* 📱 Responsive Design
* 🔐 User API Key Support
* 🎵 MP3 Audio Playback
* 🚀 Browser Based TTS Studio

---

# 🖼️ Preview

## Main Interface

* Voice Library
* AI Voice Selection
* Audio History
* Preview Playback
* Gemini TTS Models

---

# 🧠 Supported Models

| Model                | Usage              |
| -------------------- | ------------------ |
| Gemini 2.5 Flash TTS | Fast Generation    |
| Gemini 3.1 Flash TTS | High Quality Voice |
| Future Ready         | Expandable         |

---

# 🎤 Voice Library

JarvisTTS includes 30 AI voices with Indian styled names.

## Male Voices

* Aarav
* Vivaan
* Aditya
* Kabir
* Arjun
* Reyansh
* Krishna
* Rohan
* Rahul
* Dev
* Ishaan
* Aryan
* Kunal
* Siddharth
* Yash
* Ayaan

## Female Voices

* Ananya
* Priya
* Meera
* Diya
* Kavya
* Aadhya
* Riya
* Sneha
* Pooja
* Ira
* Naina
* Saanvi
* Tara
* Zara

---

# ⚙️ Tech Stack

## Frontend

* React.js
* Tailwind CSS
* JavaScript

## Backend

* Node.js
* Express.js

## APIs

* Google Gemini TTS API
* Google AI Studio API

---

# 📂 Project Structure

```bash
JarvisTTS/
│
├── public/
│   ├── audio-preview/
│   └── assets/
│
├── src/
│   ├── components/
│   ├── data/
│   ├── pages/
│   ├── utils/
│   └── App.jsx
│
├── server/
│   ├── server.js
│   └── routes/
│
├── package.json
└── README.md
```

---

# 🚀 Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/JarvisTTS.git
```

---

## 2️⃣ Open Project

```bash
cd JarvisTTS
```

---

## 3️⃣ Install Dependencies

```bash
npm install
```

---

## 4️⃣ Start Frontend

```bash
npm run dev
```

---

## 5️⃣ Start Backend

```bash
node server.js
```

---

# 🔑 API Setup

Get your API key from:

[https://aistudio.google.com/](https://aistudio.google.com/)

Create `.env`

```env
GEMINI_API_KEY=YOUR_API_KEY
```

---

# 🎵 Voice Object Example

```javascript
{
  id: "v1",
  name: "Aarav",
  gender: "Male",
  lang: "Hindi",
  geminiVoice: "Puck",
  previewUrl: "/audio-preview/aarav.mp3"
}
```

---

# 🎧 Audio Preview System

```javascript
const audio = new Audio("/audio-preview/aarav.mp3");
audio.play();
```

---

# 🛠️ Upcoming Features

* 🎙️ Real-Time Streaming TTS
* 🤖 AI Voice Cloning
* 🌍 Multi Language Expansion
* 📥 Audio Download
* ☁️ Cloud History Sync
* 📱 Android APK
* 🖥️ Desktop Version
* 🎚️ Voice Speed Control
* 🎼 Emotion Control

---

# 📸 Screenshots

Add your UI screenshots here:

```md
![Home](./screenshots/home.png)
```

---

# 🧩 Browser Autoplay Fix

If preview playback gets blocked:

```javascript
button.onclick = async () => {
  await audio.play();
};
```

---

# 🔥 Performance

* ⚡ Lightweight
* 🚀 Fast Response
* 🎧 Smooth Playback
* 💾 History Support
* 📱 Mobile Friendly

---

# 👨‍💻 Developer

### Krishna Sharma

AI Developer • Voice Assistant Creator • Full Stack Learner

---

# 📜 License

MIT License

Free to use and modify.

---

# 🌟 Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
🧠 Contribute improvements

---

# ❤️ JarvisTTS

> "Your Personal AI Voice Assistant"
