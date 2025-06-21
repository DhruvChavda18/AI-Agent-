# 🤖 Gemini-Twitter AI Agent

A **Node.js-based AI agent** that uses **Gemini LLM** to generate tweets and posts them automatically to **X (formerly Twitter)** via **Twitter API v2**. Built using `twitter-api-v2`, `dotenv`, and **MCP SDK**, this project follows a modular `client/server` structure for secure and scalable development.

---

## 🌟 Features

- 🧠 **Gemini LLM Integration** (via Gemini API)
- 🐦 **Tweet Posting** using Twitter API v2 (`twitter-api-v2`)
- 🔐 **Secure Secrets Handling** via `.env` and `dotenv`
- 🧱 **Modular Structure** with `client/` and `server/`
- 💻 **Locally Hosted**, no cloud required

---

## 🛠️ Tech Stack

- **Node.js**
- **Gemini LLM**
- **Twitter API v2**
- **twitter-api-v2** (`npm i twitter-api-v2`)
- **dotenv** (`npm i dotenv`)
- **MCP SDK** (for agent logic)

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/DhruvChavda18/AI-Agent-.git
   cd AI-Agent-

2) Install dependencies for both client and server

cd client
npm install

cd ../server
npm install

3) 🔐 Environment Variables Setup
   
/client/.env
GEMINI_API_KEY=your_gemini_api_key

/server/.env
TWITTER_API_KEY=your_twitter_api_key
TWITTER_API_SECRET=your_twitter_api_secret
TWITTER_ACCESS_TOKEN=your_access_token
TWITTER_ACCESS_SECRET=your_access_secret

4) 🚀 Running the Project

Step 1: Start the backend server
cd server
node index.js

Step 2: Start the client in new terminal
cd client
node index.js
