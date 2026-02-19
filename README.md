# WhatsApp AI Google Drive Assistant

Production-grade AI automation system that allows users to manage Google Drive files directly via WhatsApp using natural language commands.

---

## 🚀 Overview

Managing files inside Google Drive manually is slow, fragmented, and inefficient — especially on mobile.

This system transforms WhatsApp into a powerful AI-driven control layer for Google Drive, enabling users to search, upload, summarize, and manage files instantly using chat commands.

Built with **n8n + OpenAI + Twilio + Google Drive API**, this workflow demonstrates real-world automation engineering, not demo scripting.

---

## 🧠 Key Capabilities

- Natural language file search
- AI-powered document summaries
- Secure file uploads via WhatsApp
- Folder creation and management
- Context-aware AI responses
- Structured error handling and retries
- Webhook-based real-time execution

---

## 🏗 System Architecture

**User (WhatsApp) → Twilio → Webhooks → n8n → AI + APIs → Google Drive → Response back to WhatsApp**

Core components:
- n8n orchestration engine
- OpenAI API for intent detection & summarization
- Twilio WhatsApp Cloud integration
- Google Drive API
- Secure webhooks & state management

---

## 🔧 Tech Stack

- n8n (Workflow Orchestration)
- OpenAI API (LLM Intelligence)
- Twilio WhatsApp API (Messaging)
- Google Drive API
- Webhooks
- REST APIs
- JSON-based workflow state logic

---

## ⚙ How It Works (High-Level Flow)

1. User sends message on WhatsApp  
2. Twilio webhook triggers n8n workflow  
3. AI extracts user intent (search / upload / summarize / manage)  
4. n8n executes required Drive operations  
5. AI formats intelligent response  
6. Result sent back to WhatsApp in real time  

---

## 🧩 Workflow Logic

- Intent classification using LLM  
- Conditional routing via n8n  
- File system state management  
- Retry + error handling layers  
- Secure API orchestration  

---

## 🧪 Example Commands

- “Find my invoice from last month”
- “Upload this PDF to Finance folder”
- “Summarize the contract I uploaded yesterday”
- “Create a new folder called Legal Docs”

---

## 🔒 Security Considerations

- Token-based API authentication  
- Webhook validation  
- Controlled permission scopes  
- No hardcoded credentials  

---

## 📌 Use Cases

- Business document automation  
- Mobile-first file management  
- Personal AI assistants  
- Operations teams  
- Remote workforce productivity  

---

## 👤 Author

**Gurpreet Kaur — Automation Engineer | AI Workflow Architect**  

Building production-grade AI automation systems using n8n + LLMs + APIs.
