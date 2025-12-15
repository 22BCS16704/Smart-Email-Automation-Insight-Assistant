# Smart Email Automation & Insight Assistant

## 📌 Project Overview
This project automatically reads incoming Gmail emails,
summarizes them using Google Gemini AI,
and sends concise insights to WhatsApp using n8n automation.

## 🛠 Tech Stack
- n8n
- Gmail API
- Google Gemini AI
- WhatsApp Business Cloud API

## 🔁 Workflow Steps
1. Fetch emails from Gmail
2. Analyze and summarize content using AI Agent
3. Send summarized notification to WhatsApp

## ⚠️ WhatsApp Constraint
WhatsApp allows free-text messages only within a 24-hour user interaction window.
For business-initiated messages, approved message templates are used.

## 📂 Repository Contents
- `workflow.json` – Exported n8n workflow
- `screenshots/` – Workflow and node configuration screenshots

## 👩‍💻 Author
Prachi Garg

