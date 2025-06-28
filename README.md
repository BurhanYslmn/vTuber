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
```

You can also run it using the batch file:

```bash
vtuber.bat
```

---

## 🖼️ Customize Your Character

Replace the following files with your own:

- `idle.png` → Normal face (closed mouth)  
- `talking.png` → Talking face (open mouth)

---

## 📺 How to Use with OBS

1. Launch the app  
2. Open OBS → Add a **Window Capture** source  
3. Select the VTuber window  
4. Enable **“Allow transparency”**

---

## 📄 License

Licensed under the [MIT License](LICENSE) ✅  
You are free to use, modify, and share this project.
