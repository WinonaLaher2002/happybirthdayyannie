# 🎶 Happy Birthday Day Yannie! 🎂💙

A browser-based music player created as a sweet birthday and Valentine web gift.  
This project features a glassmorphism-inspired UI, smooth animations, and a playlist system that allows users to upload and permanently save their own songs using IndexedDB.

---

## 📖 Description

Happy Birthday Day Yannie! is a browser-based music player designed as a heartfelt birthday and Valentine web gift. It features a glassmorphism design, animated UI, playlist controls, and custom song uploads. Uploaded music is saved using IndexedDB, keeping the playlist even after page refresh.

---

## ✨ Features

- 🎧 Play / Pause / Next / Previous controls  
- 📜 Interactive playlist display  
- ⏱ Progress bar with current time & duration  
- 🎨 Album art preview  
- ➕ Upload custom songs and images  
- 💾 Persistent storage using IndexedDB  
- 💎 Glassmorphism UI with floating animation  
- 🌸 Cute, soft, romantic visual theme  

---

## 🛠 Technologies Used

- **HTML5** – Structure and audio playback  
- **CSS3** – Glassmorphism effects, animations, layout  
- **JavaScript (Vanilla)** – Player logic and playlist handling  
- **IndexedDB** – Local browser storage for uploaded songs  
- **Google Fonts** – Cherry Bomb One & Gaegu  

---

## 📂 Project Structure

project/
│
├── index.html
├── assets/
│ ├── flower.ico
│ ├── flower.png
│ ├── songs/
│ │ └── *.mp3
│ └── imgs/
│ └── *.jpg


---

## 🚀 How to Run

1. Download or clone the project.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox).
3. Use the music controls to play songs.
4. Add your own music using the **Add Your Song** section.
5. Refresh the page — your uploaded songs will still be there 🎉

---

## 💾 How Storage Works

- Custom songs are converted to Base64 and stored locally using IndexedDB.
- Each uploaded song is saved in the browser and automatically restored on load.
- Removing a song deletes it from both the playlist and IndexedDB.
- No backend or server is required.

---

## ⚠ Notes & Limitations

- Songs are saved **per browser only**.
- Clearing browser data will remove uploaded songs.
- Large audio files may affect performance.
- Best viewed on desktop screens.

---

## 💖 Purpose

This project was made as a **personal and creative web gift**, combining music, design, and code to express appreciation and celebration for someone special.

---

## 📜 License

This project is intended for **personal and educational use**.
