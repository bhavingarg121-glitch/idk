# AccessAll — Making the Web Accessible for Everyone 🌐🔊

**AccessAll** is a browser-based accessibility platform built to empower visually impaired, hearing impaired, and physically impaired users. It combines full webpage text-to-speech audio reading, 17+ language translation, real-time speech-to-text transcription, AI photo-to-spoken answer recognition, font scaling, and high-contrast themes into a simple interface — requiring zero software installation.

![AccessAll Screenshot](https://img.shields.io/badge/Accessibility-WCAG%202.1-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Built With](https://img.shields.io/badge/Built%20With-HTML5%20%7C%20CSS3%20%7C%20JS-orange?style=for-the-badge)

---

## ✨ Key Features

- **🔊 Webpage Text-to-Speech (Full Page Audio Reader)**:
  - Read the entire webpage out loud with one click.
  - Floating player controls (`Pause`, `Resume`, `Stop`).
  - Automatic section scrolling and visual high-contrast text highlighting as it reads.

- **🌐 Multilingual Webpage Translation**:
  - Instant full-page translation into 17+ languages:
    - 🇮🇳 **Hindi**, **Marathi**, **Bengali**, **Tamil**, **Telugu**, **Gujarati**, **Kannada**, **Malayalam**, **Punjabi**, **Urdu**
    - 🌍 **Spanish**, **French**, **German**, **Arabic**, **Japanese**, **Chinese**, **English**
  - Text-to-speech voice auto-matching to the selected target language.

- **🎤 Speech-to-Text Transcriber**:
  - Live microphone dictation turning spoken words into editable screen text.

- **📸 Photo → Spoken Answer (AI Vision & OCR)**:
  - Capture or upload photos to identify objects using TensorFlow.js (`COCO-SSD`) and read embedded image text out loud using Tesseract.js (OCR).

- **🎨 High Contrast & Typography Scaler**:
  - Atkinson Hyperlegible font scaling (`A−`, `Reset`, `A+`) for visual accessibility.
  - Ultra-bright **◐ High Contrast Theme** toggle (Black & Amber palette).

- **⌨️ 100% Keyboard Accessible**:
  - Full keyboard control (`Tab`, `Enter`, `Space`) with high-visibility focus rings across all controls.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5 (Semantic & ARIA), Vanilla CSS3 (Custom Properties, Glassmorphism, Responsive Grid), JavaScript (ES6+).
- **Typography**: Atkinson Hyperlegible (Braille Institute visual legibility font) & Space Grotesk.
- **Browser APIs**: Web Speech API (`SpeechSynthesis` & `SpeechRecognition`), DOM `TreeWalker`, MediaDevices API, Canvas API, IntersectionObserver API.
- **AI & ML**: TensorFlow.js, COCO-SSD object detection, Tesseract.js OCR, MyMemory Translation API.

---

## 🚀 How to Run Locally

No build tools or NPM dependencies required!

1. Clone this repository:
   ```bash
   git clone https://github.com/bhavingarg121-glitch/idk.git
   cd idk
   ```

2. Serve using any web server or Python:
   ```bash
   python -m http.server 8080
   ```

3. Open **`http://localhost:8080/index.html`** in Chrome, Edge, or Firefox.

---

## 🏫 Project Details

* **Institution**: Department of Computer Science and Engineering, Priyadarshini College of Engineering, Nagpur.
* **Team**: Sanchita Moundekar, Khushi Karemore, Riddhi Sarosiya, Adhitya Anil and Saloni Singh.
* **License**: MIT
