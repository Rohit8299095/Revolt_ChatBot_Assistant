# Revolt ChatBot Assistant (Gemini Live API)

A real-time conversational voice chatbot replicating the functionality of Revolt Motors' voice assistant, built using Google Gemini API with Node.js and WebSockets.

---

## ​ Features
- 🎤 **Voice Interaction** – Speak to the bot and get spoken responses.
- 🔄 **Auto Listen Mode** – After each bot response, it auto-starts listening for the next question.
- ⏹ **Interrupt Support** – Click the mic button to stop bot speech and start new input instantly.
- 🖋 **Text Chat Support** – You can also type queries.
- 🌐 **Clean Modern UI** – Responsive and minimal design.

---

## ​ Tech Stack
**Backend:** Node.js, Express, WebSocket  
**Frontend:** HTML, CSS, JavaScript  
**API:** Google Gemini (Audio Dialog)

--

## ​ Setup Instructions

1. **Clone the repository:**

   git clone https:https://github.com/Rohit8299095/Revolt_ChatBot_Assistant.git
   cd Revolt_ChatBot_Assistant
2. **Install dependencies:**
      npm install
      
3.**Add your Gemini API Key:**
     Create a .env file in the root folder:
     GEMINI_API_KEY=your_google_api_key_here

     Get your API Key from Google AI Studio.
4.**Start the Server:**
      npm start

5.**Open in browser:**
      http://localhost:3000
      


## ✅ Demo Video
[🎥 **Watch Demo Here**](https://drive.google.com/file/d/1qsxsNyI9a_jowB6YQZ0u-tx6Q_8fkimC/view?usp=drive_link)

---

## 📁 Folder Structure

REVOLT-ChatBot-ASSISTANT/
│
├── node_modules/
│
├── Public/
│   ├── client.js       # Client-side JS logic
│   ├── index.html      # Frontend UI
│   └── style.css       # Styling
│
├── Server/
│   └── index.js        # Backend server code
│
├── .env                # API Key (Do NOT upload to GitHub)
├── .env.example (ignore it)
├── package-lock.json
├── package.json
└── README.md


---

## ✅ How It Works
1. 🎤 User speaks → Mic captures voice → Converts to text → Sends to server.  
2. 🔗 Server calls **Gemini Live API** with the text.  
3. 💬 API responds → App speaks & displays the result in real-time.

---

### Author
Made with ❤️ by *Rohit Kumar*
