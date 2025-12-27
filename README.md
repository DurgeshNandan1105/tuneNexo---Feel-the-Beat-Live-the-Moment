🎧 TuneNexo – Full-Stack Music Streaming Website

TuneNexo is a Spotify-inspired full-stack music streaming platform built using React, TypeScript, Node.js, Express, MongoDB, Zustand, Socket.io, and Vite.
Users can listen to songs, manage albums, chat in real-time, create profile sessions, and enjoy a modern UI-UX music experience.

🚀 Live Demo

🔗 Demo Link: https://tunenexo-feel-the-beat-live-the-moment.onrender.com/

📌 Features
🎵 Music Player

Play / Pause / Seek / Next / Previous

Volume control & timeline progress bar

Auto-queue & album-based playback

🛠 Authentication

Google OAuth Login

Protected private routes

Persistent sessions

💬 Real-Time Chat

Live messaging using Socket.io

Online user indicators

Friend activity sidebar

🖼 Albums & Songs

Dynamic album and track management

Song cover images & metadata

🌐 UI/UX

Fully responsive layout

Left sidebar + top navigation + central player

Smooth animations & modern theme

🏗 Project Structure
tuneNexo/
│
├── backend/
│   ├── src/
│   │   ├── index.js
│   │   └── ...
│   ├── .env.sample
│   ├── package.json
│   └── ...
│
├── frontend/
│   ├── public/
│   │   ├── albums/
│   │   ├── cover-images/
│   │   ├── songs/
│   │   ├── google.png
│   │   ├── tuneNexo.png
│   │   └── ...
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── AudioPlayer/
│   │   │   ├── FriendActiveBar/
│   │   │   ├── LeftSidebar/
│   │   │   ├── PlaybackControls/
│   │   │   ├── Topbar/
│   │   │   └── ...
│   │   ├── layout/MainLayout.tsx
│   │   ├── pages/
│   │   │   ├── 404/NotFoundPage.tsx
│   │   │   ├── admin/AdminPage.tsx
│   │   │   ├── album/AlbumPage.tsx
│   │   │   ├── auth-callback/AuthCallback.tsx
│   │   │   ├── chat/ChatPage.tsx
│   │   │   ├── home/HomePage.tsx
│   │   │   └── ...
│   │   ├── providers/AuthProvider.tsx
│   │   ├── stores/
│   │   │   ├── useMusicStore.ts
│   │   │   ├── usePlayerStore.ts
│   │   │   ├── useChatStore.ts
│   │   │   └── ...
│   │   ├── lib/axios.ts
│   │   ├── types/
│   │   ├── App.tsx
│   │   └── ...
│   ├── package.json
│   └── ...
│
└── README.md

📜 License

This project is for educational purposes only.
All rights to songs and media belong to their respective owners.

👨‍💻 Author

👤 Durgesh Nandan
💼 Developer | MERN Stack 
