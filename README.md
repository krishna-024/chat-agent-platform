# Chat Agent Platform for Developers

A plug-and-play platform that helps developers build custom chat agents powered by LLMs (OpenAI, Groq, Anthropic) and Contentstack.

## 🚀 Features
- LLM API that connects to Contentstack Delivery API
- Chat SDK with React Hooks
- Plug-and-play Chat UI
- Demo travel chatbot example

## 🛠 Tech Stack
- Backend: Node.js + Express
- Frontend SDK: React
- CMS: Contentstack
- LLM Providers: OpenAI, Anthropic, Groq (extensible)

## 📂 Structure
- `backend/` → LLM API
- `sdk/` → React SDK
- `demo-app/` → Travel chatbot demo

## ▶️ Run Locally
1. Clone the repo
2. Install backend deps:
   ```bash
   cd backend
   npm install
   npm start
   ```
3. Install SDK (for local linking):
   ```bash
   cd sdk
   npm install
   npm link
   ```
4. Run demo app:
   ```bash
   cd demo-app
   npm install
   npm link chat-agent-sdk
   npm start
   ```

## 📹 Pitch Video
- Explain problem, show demo, and highlight impact.
