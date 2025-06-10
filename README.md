# 🧠 AI Article Summarizer Chrome Extension

**AI-Article-Summarizer** is a lightweight Chrome extension that helps you quickly summarize articles using Google's Gemini AI. Whether you want a brief overview, a detailed explanation, or bullet-point takeaways, this tool makes it easy to digest web content in seconds.

---

## 🚀 Features

- 🔍 **Auto-detects article content** from any webpage  
- 📋 **Three summary types**: Brief, Detailed, and Bullet Points  
- ⚡ **Google Gemini API Integration** for fast and accurate summaries  
- 🧰 Simple and elegant **popup interface**  
- 🔑 Save and manage your API key using a **secure options page**  
- 📎 **Copy-to-clipboard** functionality for quick sharing  

---

## 📁 Directory Structure

```

lohitkumar1914-ai-article-summarizer/
├── README.md
├── background.js        # Opens options page on install if API key is missing
├── content.js           # Extracts article text from the active page
├── manifest.json        # Chrome extension manifest (v3)
├── options.html         # UI for saving the Gemini API key
├── options.js           # Logic to save and validate API key
├── popup.html           # UI for summary options and display
├── popup.js             # Handles summarization and interaction with the API

````

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/lohitkumar1914/ai-article-summarizer.git
cd ai-article-summarizer
````

### 2. Load Extension in Chrome

1. Open Chrome and go to `chrome://extensions/`
2. Enable **Developer Mode** (toggle in top right corner)
3. Click **"Load unpacked"**
4. Select the `lohitkumar1914-ai-article-summarizer` folder

---

## 🔐 Get Your Gemini API Key

1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Sign in and generate an API key
3. Copy the key
4. After installing the extension, the options page will open automatically. Paste your API key there and save.

---

## 📚 How to Use

1. **Navigate to any article page**
2. **Click the extension icon**
3. Choose a summary type:

   * `Brief` – 2–3 sentence overview
   * `Detailed` – More comprehensive explanation
   * `Bullet Points` – 5–7 concise highlights
4. Click **"Summarize This Page"**
5. View the summary or click **"Copy Summary"** to share

---

## 📦 Technologies Used

* 🧩 Chrome Extension Manifest V3
* 🧠 Google Gemini API (via [generativelanguage.googleapis.com]((https://aistudio.google.com/)))
* ⚙️ JavaScript, HTML, CSS

---


## 📷 Screenshots


![image](https://github.com/user-attachments/assets/fdb02f91-f654-45ef-9043-164534d6b928)
