# n8n AI Assistant Workflow

This repository contains a customizable **n8n workflow** that integrates an AI assistant powered by LangChain and OpenRouter (GPT 4.1 mini) with Google Sheets, Gmail, and Google Calendar.

## 🧠 Features

- Triggered via a chat interface
- AI Assistant executes tasks like:
  - Looking up contact details in a Google Sheet
  - Sending emails using Gmail
  - Creating calendar events in Google Calendar
- Utilizes `Simple Memory` for short-term conversation context

## 📁 Workflow Overview

The workflow includes the following nodes:
- **Trigger**: Starts when a chat message is received
- **AI Agent**: Responds and acts based on system instructions
- **Language Model**: DeepSeek via OpenRouter
- **Memory**: Buffer-based memory to maintain context
- **Google Sheets**: Used as a contact database
- **Gmail**: Sends emails
- **Google Calendar**: Schedules events

## ⚠️ Setup Instructions
WORKFLOW!!
![Screenshot 2025-06-03 135320](https://github.com/user-attachments/assets/68a58b37-7d4f-4fa7-a160-828172f5a781)


1. **Install n8n** (if not already):  
   [Installation Guide](https://docs.n8n.io/hosting/installation/)

2. **Import the Workflow**:
   - Open your local or hosted n8n instance.
   - Click on `Import Workflow` and upload the sanitized `.json` file.

3. **Set Up Credentials**:
   - **Google Sheets API**
   - **Gmail OAuth2**
   - **Google Calendar OAuth2**
   - **OpenRouter API Key**

4. **Update References**:
   - Replace placeholders like `"your-google-sheet-id"` and `"your-calendar@example.com"` with your actual values.


