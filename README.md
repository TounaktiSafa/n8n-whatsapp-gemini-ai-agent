# 🤖 n8n WhatsApp + Google Gemini AI Agent

This repository contains an **n8n workflow** that connects **WhatsApp** with **Google Gemini AI** to create an interactive conversational agent.  

The workflow allows users to send WhatsApp messages, process them with a **LangChain-powered AI Agent** backed by Google Gemini, maintain short-term memory, and respond back via WhatsApp automatically.

---

## 🚀 Features
- 📲 **WhatsApp Trigger**: Starts the workflow when a new message is received.  
- 🧠 **AI Agent (LangChain)**: Manages interactions and routing.  
- 💬 **Google Gemini Chat Model**: Provides natural language responses.  
- 📝 **Memory Buffer**: Maintains short-term conversation context.  
- 📤 **Send Message**: Replies back to the user on WhatsApp.  

---

## 🛠️ Prerequisites
- [n8n](https://n8n.io/) installed locally or hosted.
- A configured **WhatsApp Business API account**.
- A **Google Gemini API key** (via Google PaLM/Gemini API).
- Credentials set up inside n8n:
  - `WhatsApp OAuth account`
  - `Google Gemini (PaLM) API account`
  - `WhatsApp API account`


