# AgentAI

AgentAI is an AI-powered web application that integrates a React frontend with a Node.js backend and MCP (Model Context Protocol) server to enable intelligent chat interactions, web search, and document-based Q&A.

---

## 🚀 Features

* AI Chat Interface
* MCP (Model Context Protocol) integration
* Web search using SerpAPI
* PDF upload and document question answering
* Modular React component architecture

---

## 🧠 Tech Stack

### Frontend

* React
* JavaScript
* Create React App

### Backend

* Node.js
* MCP (Model Context Protocol)
* LangChain
* SerpAPI

---

## 📁 Project Structure

```
agentai
│
├── server
│   ├── server.js
│   ├── mcp-server.js
│   ├── chat-mcp.js
│
├── src
│   ├── components
│   │   ├── ChatComponent.js
│   │   ├── PdfUploader.js
│   │   └── RenderQA.js
│
├── public
│
├── package.json
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```
git clone https://github.com/congruigao/agentai.git
```

Go into the project

```
cd agentai
```

Install dependencies

```
npm install
```

---

## ▶️ Run the Project

Start the development server

```
npm run dev
```

Frontend will run at:

```
http://localhost:3000
```

---

## 🔑 Environment Variables

Create a `.env` file in the `server` folder and add your API keys.

Example:

```
SERPAPI_KEY=your_serpapi_key
OPENAI_API_KEY=your_openai_key
```

⚠️ Never commit `.env` files to GitHub.

---

## 📌 Future Improvements

* RAG (Retrieval Augmented Generation)
* Vector database integration
* Memory for AI conversations
* Multi-tool AI agent workflow
* Cloud deployment

---

## 👤 Author

Congrui Gao

GitHub:
https://github.com/congruigao
