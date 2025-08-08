# n8n AI Agent & Automation Workflows

This repository contains ready-to-use **n8n automation workflows** created by **Mareeswari (Genaimarees)**.  
The workflows are focused on **AI Agents, RAG pipelines, Telegram automation, GitHub-Discord integrations**, and other productivity tasks.

---

## 📂 Repository Contents

| File Name | Description |
|-----------|-------------|
| **MCP.json** | AI Agent workflow for MCP tool integration. |
| **RAG agent 2.0.json** | Retrieval-Augmented Generation (RAG) AI Agent workflow with enhanced search and knowledge base capabilities. |
| **Telegram Voice ai agent1.json** | Telegram bot workflow with **voice-to-text AI** conversion using OpenAI Whisper and AI-generated replies. |
| **basic telegram automation.json** | Basic Telegram automation bot for sending and receiving text messages. |
| **github commit to discord.json** | Automation that sends **GitHub commit messages** to a Discord channel via webhook. |

---

## 🚀 How to Use

### 1️⃣ Import Workflows into n8n
1. Open your **n8n** dashboard.
2. Click **Import from File**.
3. Select the `.json` file you want to import.
4. Save and **Activate** the workflow.

### 2️⃣ Required Setup
- **n8n** installed (Cloud or Self-Hosted)
- API Keys for:
  - OpenAI (for AI features like GPT & Whisper)
  - Telegram Bot API (via BotFather)
  - Discord Webhook URL
  - GitHub Webhooks (for commit notifications)
- Any other service credentials depending on the workflow.

### 3️⃣ Running the Workflows
- Make sure the **Trigger Node** is set correctly (Webhook, Cron, or API).
- Ensure required environment variables and credentials are configured in n8n.
- Activate the workflow.

---

## 🛠 Features
- 🤖 **AI Agent** workflows for natural language processing and RAG search.
- 🎤 **Voice to AI Chat** integration for Telegram using OpenAI Whisper.
- 📢 **GitHub → Discord** commit notifications.
- 💬 **Basic Telegram Bot** automation.
- 📂 Modular JSON workflows, ready for import.

---

## 📌 Notes
- Each workflow is independent — you can import only what you need.
- You can modify nodes, triggers, and API keys to suit your project.
- Keep your API keys safe; do not commit them to public repos.

---

## 📜 License
This repository is for **educational and personal use**.  
You can modify and use these workflows, but please give credit to **Mareeswari (Genaimarees)** if you share them.

---
