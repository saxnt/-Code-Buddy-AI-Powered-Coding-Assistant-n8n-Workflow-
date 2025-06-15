# Code Buddy – AI-Powered Coding Assistant (n8n Workflow)

Code Buddy is a smart AI agent integrated with **n8n** and **Telegram** that can generate, debug, and explain code using natural language instructions.

## 🌟 Features

- Generate clean code in multiple programming languages
- Modify or debug existing code
- Explain the logic behind code snippets
- Telegram integration for real-time interactions
- No plugin or local environment required

## 🧠 Tech Stack

- [n8n](https://n8n.io/) – Workflow automation platform
- [OpenAI API (GPT-4)](https://platform.openai.com/)
- Telegram Bot API
- JavaScript-based expressions inside n8n nodes


## 🔄 How It Works

1. A user sends a plain-text coding request via Telegram.
2. The request triggers n8n, which passes it to the AI Agent (OpenAI node).
3. Code Buddy generates:
   - Code block
   - Logic explanation
   - Optional documentation
4. The formatted output is sent back to the user via Telegram.

## 🧪 Sample Prompts

