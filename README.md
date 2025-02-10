# Telegram-Bot-using-OpenAI

This repository contains a Telegram bot that leverages OpenAI's GPT-3.5/4 to provide intelligent responses to user queries. The bot can echo user messages and also engage in meaningful conversations powered by AI.

## **Features**
- 🛠️ **Echo Bot**: Simple bot that echoes back user messages.
- 🤖 **AI Chatbot**: Uses OpenAI's API to generate human-like responses.
- 🗑️ **Clear Conversation**: Users can reset chat history using `/clear`.
- ℹ️ **Help Command**: Displays available commands.
- 📌 **Persistent Context**: Retains past conversation history for improved AI responses.

- ## **Tech Stack**
- **Python** 🐍
- **Aiogram** (Telegram bot framework)
- **OpenAI API** 🤖
- **Dotenv** (For managing environment variables)
- **Logging** (For debugging and monitoring)

- How It Works
  
📌 Echo Bot (echo_bot.py)
A basic bot that responds with the same message the user sends.

Commands:
/start - Start the bot
/help - Display help message
Any message → Echoes back

🤖 AI Chatbot (main.py)
Uses OpenAI GPT API for responses.
Maintains previous conversation context.

Commands:
/start - Start conversation
/help - Display help message
/clear - Clear conversation history
Any message → AI-generated response

Bot Commands
Command	Description
/start	Start the conversation
/help	Show help menu
/clear	Reset chat history
text	AI-generated response
