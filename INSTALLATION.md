# Installation Guide

## Prerequisites

- n8n
- Google Gemini API Key
- Google Drive Account
- Google Sheets Account

---

## Setup

1. Clone or download this repository.

2. Import the n8n workflow into your workspace.

3. Configure credentials:
   - Google Drive
   - Google Sheets
   - Google Gemini

4. Upload the Markdown knowledge base files to Google Drive.

5. Execute the Knowledge Base Ingestion pipeline once.

6. Start the Enterprise AI Agent workflow.

7. Open the chat interface and begin asking questions.

---

## Example Questions

- What are the company working hours?
- Apply two days leave.
- Can I claim travel expenses?
- My laptop is not working.
- Show remaining leave balance.

---

## Notes

This project uses Retrieval-Augmented Generation (RAG). The AI Agent answers only from the internal company knowledge base and connected business tools.
