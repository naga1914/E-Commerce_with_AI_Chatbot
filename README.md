AI-Powered E-commerce Chatbot with Voice & Smart Shopping Assistant
This AI-powered chatbot makes online shopping easier, smarter, and more fun. Built with the MERN stack and Gemini API, it understands what you say—via text or voice—then speaks back naturally. It compares products across popular sites like Amazon, Flipkart, and Meesho, summarizes reviews, explains product quality simply, and helps you find the best deals, all in your preferred language and tone.

Why This Chatbot Stands Out
Unlike basic bots, this is your real shopping buddy:

Talks like a human, not a robot

Understands your needs naturally, even casual chat

Compares live prices and reviews from multiple platforms

Explains pros, cons, and quality clearly

Responds with AI-generated voice you can customize

Supports multiple Indian languages

Lets you chat playfully and get smart suggestions

Main Features
🎤 Voice Chat
Talk to the bot using your microphone

Bot replies with natural AI voice (TTS)

Choose voice style: female, male, energetic, calming, or your own cloned voice

💬 Natural Conversation
Say things like “I want budget shoes with good comfort”

The bot understands and responds like a friendly assistant

🌏 Language Options
Supports Hindi, Tamil, Telugu, Kannada, and more

Language is simple, friendly, and modern—not formal or old-fashioned

🛒 Smart Product Search & Comparison
Ask for products by budget, features, or brand

See live price comparisons and ratings across Amazon, Flipkart, Meesho

Know which site has the best deal and why

📋 Review Summaries & Sentiment
Gets pros and cons from hundreds of reviews

Shows visual sentiment charts (positive, neutral, negative)

Explains if a product is worth buying in your chosen tone

🎁 Gift Suggestions
Ask for gift ideas by occasion, budget, and recipient

🔔 Price Drop Alerts
Save products and get notified when prices fall

🧠 Play Mode
Chat casually, ask jokes or random questions

Explore cool deals like chatting with a friend

Tech Stack
Frontend: React.js + Tailwind CSS + Framer Motion

Backend: Node.js + Express.js

Database: MongoDB

AI: Gemini API (chat, review summarization, voice generation)

Speech Recognition: Web Speech API / Whisper

Text-to-Speech: ElevenLabs / Gemini TTS

Voice Cloning: OpenAI Voice or PlayHT

Translation: Google Translate API / Custom models

Data: Amazon, Flipkart, Meesho (via APIs or scrapers)

How to Run Locally
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/ai-ecom-chatbot.git
cd ai-ecom-chatbot
Install dependencies

bash
Copy
Edit
# Backend
cd server
npm install

# Frontend
cd ../client
npm install
Add environment variables (server/.env)

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
VOICE_CLONE_API_KEY=your_voice_api_key
Start the project

bash
Copy
Edit
# Start backend
cd server
npm run dev

# Start frontend
cd ../client
npm start
Open your browser at http://localhost:3000 and start shopping with your AI voice assistant!

Project Structure
bash
Copy
Edit
ai-ecom-chatbot/
├── client/      # React frontend (chat UI, voice, product views)
├── server/      # Express backend (APIs, Gemini integration)
├── scraper/     # Scrapers for prices and reviews
├── voice/       # Text-to-speech, speech-to-text, voice cloning logic
└── README.md

---

## 👤 About Me

I’m **Nagarani**, a MERN developer and AI enthusiast building futuristic shopping tools.  
This project is part of my journey to combine AI with real user experience in shopping.  
Feel free to explore, fork, or connect:

- GitHub: [https://github.com/naga1914](https://github.com/naga1914)  
- LinkedIn: [https://linkedin.com/in/nagarani1914](https://linkedin.com/in/nagarani1914)
