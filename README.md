# QuiPro 🎯 – AI Quiztion Helper 

**QuiPro** is a lightweight, AI-powered desktop app built with **Electron.js**. It monitors your clipboard, detects copied MCQs or open-ended questions, and instantly shows the answer using **Gemini 1.5 Pro API** in a floating overlay window.

No clicks. No lag. Just copy and win. *(For ethical/educational use only)*

---

## ⚡ Features

- ✂️ **Clipboard Detection** – Detects text as soon as it's copied.
- 🤖 **AI-Powered Answers** – Uses Gemini 1.5 Pro to respond with accurate answers.
- 💬 **Floating Overlay UI** – Minimal always-on-top display for real-time answers.
- ♻️ **Caching** – Avoids duplicate API requests using smart memory management.
- 🔁 **API Key Rotation** – Handles multiple keys to bypass rate limits.
- 🕒 **Rate-Limit Handling** – Auto cooldown to prevent 429 errors.
- 🧠 **Efficient Memory Use** – LRU-based cache to manage repeated queries.

---

## 🛠️ Tech Stack

- 🧩 **Electron.js** – Cross-platform desktop framework  
- 🧠 **Gemini 1.5 Pro** – Google’s AI model via API  
- 📝 **dotenv** – For managing environment variables  
- 📋 **Clipboardy** – Node module to read clipboard  
- 🧰 **Node.js** – App logic and Gemini integration  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Asterior/AIQuizHelper-api.git
cd AIQuizHelper-api
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Enable Clipboard History (Windows Only)

- Press `Windows + V`  
- Click **"Turn on"** clipboard history

### 4. Set Up Environment Variables

Create a `.env` file in the root folder with the following:

```env
GEMINI_API_KEY_1=your_first_key
GEMINI_API_KEY_2=your_second_key
```

> Add more keys like `GEMINI_API_KEY_3`, `GEMINI_API_KEY_4`, etc., if needed.

### 5. Run the App

```bash
npm start
```

> Now just copy any question from anywhere – the answer overlay will pop up automatically.

---




## ⚠️ Disclaimer

QuiPro is intended **for educational and research purposes only**.  
The creators are **not responsible** for misuse during exams or assessments.  
Use responsibly and ethically.

---

## 📜 License

MIT License
