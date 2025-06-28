# 🧠 Reminderly — Offline Voice-Assisted Smart Reminder App

**Reminderly** is a cross-platform mobile reminder application that delivers smart task management and audio notifications — all while working completely offline. Built using React Native, FastAPI, and SQLite, it offers a privacy-focused experience for creating, storing, and managing reminders on-device.

---

## 🚀 Features

- 🔊 **Text-to-Speech Playback**  
  Reminders are read aloud using Expo's TTS engine — perfect for accessibility and hands-free operation.

- 📴 **Fully Offline Compatibility**  
  No cloud, no sync — all data is stored locally using SQLite and handled by a FastAPI backend.

- 🧩 **Modular UI Design**  
  Includes well-structured screens: Login, Register, Dashboard, Edit Reminder, and Settings.

- 🔐 **Privacy-First Architecture**  
  Entire stack is offline and self-contained — designed with user privacy at the core.

- 🎙️ **Planned: Voice-Based Reminder Creation (STT)**  
  Voice input integration using Expo’s Speech-to-Text API is in progress to enable hands-free task creation.

- 🤖 **Future Integration with Project AARNA**  
  Reminderly is being adapted into a modular agent for AARNA — to function as a voice-controlled task assistant.

---

## 🛠️ Tech Stack

- **Frontend:** React Native (Expo), Tailwind CSS  
- **Backend:** FastAPI (Python)  
- **Database:** SQLite (Local Device Storage)  
- **Voice Module:** Expo Text-to-Speech (TTS)  
- **State Management:** React Context API  

---

## ⚙️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/VB1408/reminderly.git
cd reminderly

# Install dependencies and start the frontend
npm install
npx expo start

# Navigate to backend and run FastAPI
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
