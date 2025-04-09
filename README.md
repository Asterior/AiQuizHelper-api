# QuiPro – AI Quiz Helper

QuiPro is a lightweight, AI-powered desktop application built using **Electron.js**. It monitors your clipboard for any copied quiz questions (MCQs or open-ended) and instantly displays intelligent answers using the **Gemini API** in a sleek overlay window. Designed for speed and stealth – perfect for live quiz environments(Ethical purposes only) or instant study support.

---

## ⚙️ Features

- ✂️ **Auto Clipboard Detection** – Triggers instantly when text is copied.
- 🤖 **AI-Powered Responses** – Uses Gemini 1.5 Pro to generate smart, concise answers.
- 💬 **Floating Overlay Window** – Non-intrusive, always-on-top response box.
- ♻️ **Response Caching** – Avoids repeated API calls for the same question.
- 🔁 **API Key Rotation** – Uses multiple keys to bypass rate limits.
- 🕒 **Rate-Limit Handling** – Automatic cooldown to prevent abuse and avoid 429 errors.
- 🧠 **Efficient Memory Use** – LRU-style cache with size limit.

---

## 🚀 Getting Started

### 1. Clone the repo and type "npm install"
### 2. Turn on Clipboard history (windows+V)
### 3. Add your API keys in the .env file (recommended to add 2 api keys to avoid hitting rate limits or can make multiple keys and add them if you are using a free one)
### 4. Open the terminal and type npm start and you are good to when you copy you will see the overlay automatically pop up and answer your question

```bash
git clone https://github.com/Asterior/AIQuizHelper-api.git
cd AIQuizHelper-api
----
