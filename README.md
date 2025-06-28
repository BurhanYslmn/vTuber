# 🎙️ VTuber Electron App

This project is a simple PNGTuber app that moves the character’s mouth when you speak using microphone input.  
It is OBS-compatible and thanks to Electron, it continues to respond even in the background.

---

## 🧩 Features

- 🎤 Microphone detection  
- 👄 2D character mouth animation when speaking  
- 🖥️ Transparent window (perfect for OBS)  
- 💤 Stays idle while silent, animates on sound  
- 🔊 Keeps working even when window is not focused  

---

## 🔧 Installation

> 💡 To run this project, install [Node.js](https://nodejs.org) (LTS version).  
Then in the terminal, run:

```bash
npm install
npm start
Alternatively, just double-click:

bash
Kopyala
Düzenle
vtuber.bat
🖼️ Customize Your Character
Replace the two images with your own:

plaintext
Kopyala
Düzenle
idle.png     →  Normal face (mouth closed)  
talking.png  →  Talking face (mouth open)
You can draw your own or create them online (e.g. Charat, Picrew).

📺 How to Use with OBS
Launch the app

Open OBS and add a Window Capture source

Select the VTuber Electron window

Check “Allow transparency” box ✅

📄 License
This project is licensed under the MIT License.
You are free to use, modify, distribute, and share it — no restrictions ✅