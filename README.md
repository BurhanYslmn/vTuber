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

1. Download or clone this project  
2. Open terminal and go to the folder:
   ```bash
   npm install

3. Then Start the app:

npm start

Alternatively, just double-click vtuber.bat to launch.

🖼️ Customize Your Character
To use your own character, just replace these two images:

- idle.png — Normal (mouth closed)

- talking.png — Talking (mouth open)

You can draw your own or generate them with online tools.

📺 How to Use with OBS
Run the app

In OBS, add a "Window Capture" source

Select the Electron VTuber window

Enable "Allow transparency"

That’s it — your character will now animate based on your voice! 🎉

📄 License
This project is licensed under the MIT License.
You are free to use, modify, distribute, and share it — no restrictions ✅

# 🎙️ VTuber Electron App

Bu proje, mikrofonla ses algılayarak konuşma esnasında ağzı oynayan basit bir PNGTuber uygulamasıdır.  
OBS ile uyumlu çalışır ve Electron sayesinde arka planda bile tepki verir.

---

## 🧩 Özellikler

- 🎤 Mikrofon algılama
- 👄 Konuşunca ağzı oynayan 2D karakter
- 🖥️ Şeffaf pencere (OBS için uygun)
- 💤 Sessizken durur, konuşunca hareket eder
- 🔊 Arka planda çalışmayı destekler

---

## 🔧 Kurulum

1. Bu projeyi indir / klonla
2. Terminalde klasöre gir:
   
bash
   npm install
3. Çalıştırmak için
npm start

Alternatif olarak vtuber.bat dosyasına çift tıklayarak da çalıştırabilirsin.

Kendi karakterini Yerleştirmek için sadece Alttaki 2 dosyayı değiştir.

idle.png — Karakterin normal hali
talking.png — Konuşurkenki hali

Görselleri sen oluşturabilir veya örneklerle değiştirebilirsin.

📺 OBS Kullanımı
1. Uygulamayı çalıştır

2. OBS'de "Pencere Yakalama (Window Capture)" kaynağı ekle

3. Electron uygulamasını seç

4. "Şeffaflığı destekle" kutusunu işaretle

📄 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
İsteyen herkes kullanabilir, geliştirebilir, paylaşabilir ✅