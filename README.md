# 🎙️ Audio Transcription App

A simple web application built with **React + Vite** that allows users to upload audio files and receive transcriptions.  
The project demonstrates modern frontend development with Vite, React, and Axios for API communication.

---

## 🚀 Features
- Upload audio files from your device
- Send audio files to a backend API for transcription
- Display transcription results in a clean, minimal UI
- Responsive design with custom CSS

---

## 🛠️ Tech Stack
- **Frontend:** React, Vite
- **HTTP Client:** Axios
- **Styling:** CSS
- **Containerization:** Docker & Docker Compose (for local development)

---

## 📦 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/audio-transcription-app.git
cd audio-transcription-app
```

### 2. Install dependencies

If running locally (without Docker):
```
npm install
```

### 3. Run the app
npm run dev


The app will be available at: http://localhost:5173

### 🐳 Running with Docker

Build & start containers:

```bash
docker-compose up --build
```

The app will be available at: http://localhost:5173



📂 Project Structure
```
audio-transcription-app/
├── src/
│   ├── App.jsx
│   ├── AudioUploader.jsx   # Upload & transcription logic
│   ├── index.css           # Global styles
│   └── main.jsx            # Entry point
├── public/                 # Static assets
├── package.json
├── docker-compose.yml
├── Dockerfile
└── README.md
```


### ⚡ Improvements (Future Scope)

- Add backend (Node/Express or FastAPI) with real transcription support (e.g., OpenAI Whisper API)
- Support multiple file formats (mp3, wav, etc.)
- Show progress bar during upload
- Store transcription history
- Add authentication for users
