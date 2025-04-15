# 🎧 Lyrics Finder

**Lyrics Finder** is a full-stack music streaming and lyrics application that allows users to search for songs, stream audio, view synchronized lyrics, and receive AI-powered music recommendations based on mood or context.

---

## ✨ Features

- 🔍 **Search Songs** by title, artist, or lyrics  
- 📝 **Synchronized Lyrics** fetched from Genius  
- 🎶 **Stream Audio** directly from YouTube  
- 🤖 **AI Music Assistant** powered by Hugging Face  
- 🧠 **Mood-based Recommendations** (happy, sad, romantic, energetic)  
- 📂 **Playlist Support** *(upcoming)*  

---

## 🧱 Tech Stack

| Layer     | Technologies Used                           |
|-----------|---------------------------------------------|
| Frontend  | React, Vite, Tailwind CSS                   |
| Backend   | Node.js, Express.js                         |
| AI/ML     | Hugging Face Transformers API               |
| Lyrics    | Genius API, LyricsGenius (Python)           |
| Audio     | YouTube (via yt-dlp)                        |
| Python    | Flask                                       |

---

## 📁 Project Structure

lyrics-finder/ ├── client/ # React + Vite frontend │ ├── src/ │ │ ├── components/ # UI components │ │ ├── context/ # React Context API │ │ ├── pages/ # App pages │ │ ├── services/ # API services │ │ ├── App.jsx │ │ ├── main.jsx │ │ └── index.css │ ├── index.html │ └── vite.config.js

├── server/ # Node.js + Express backend │ ├── src/ │ │ ├── controllers/ │ │ ├── routes/ │ │ └── index.js │ ├── .env │ └── package.json

├── python/ # Flask-based audio/lyrics microservice │ ├── audio_service.py │ ├── requirements.txt │ └── .env



---

## ⚙️ Setup & Installation

### ✅ Prerequisites

- Node.js v16+
- Python v3.8+
- npm or yarn
- Flask & pip
- yt-dlp (installed via `requirements.txt`)

---

### 📦 Clone the Repository



🌍 Environment Variables Summary
File	Variable	Description
server/.env	PORT	Backend port (default: 5001)
GENIUS_API_KEY	Genius API key
client/.env.local	VITE_FIREBASE_API_KEY	Firebase API key (if used)
VITE_HUGGING_FACE_API_KEY	Hugging Face API key
python/.env	GENIUS_ACCESS_TOKEN	Genius token for lyricsgenius
HUGGING_FACE_API_KEY	Hugging Face API key



🧪 Usage
Start Python microservice

Run the backend server

Launch the frontend

Visit http://localhost:5173 to explore the app


👨‍💻 Authors







🤝 Contributing
Contributions are welcome! Please fork the repo and open a PR.

🍴 Fork the repository

🛠️ Make your changes

🚀 Open a pull request



This project is licensed under the MIT License
