# 🤖 Telegram AI Chatbot

A self-hosted AI chatbot built using:
- n8n
- Telegram Bot API
- OpenRouter AI
- Docker
- DigitalOcean
- Caddy SSL Reverse Proxy

The bot receives Telegram messages, processes them using an AI model, and sends intelligent responses back automatically.

---

# 🧠 Workflow Architecture

Telegram User
      ↓
Telegram Trigger
      ↓
Basic LLM Chain
      ↓
OpenAI Chat Model (OpenRouter)
      ↓
Telegram Send Message

---

# 📸 Screenshot

<img width="1240" height="545" alt="image" src="https://github.com/user-attachments/assets/9ec05a95-9af0-44b8-b65a-ac80cc3573fe" />

---

# 📂 Project Structure

```text
telegram-ai-chatbot/
│
├── workflows/
│   └── telegram-ai-bot.json
│
├── screenshots/
│   └── workflow.png
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

# 🧪 Future Improvements

- Conversation memory
- Voice messages
- RAG chatbot
- PDF knowledge base
- Website chatbot
- WhatsApp integration
- AI agents
- Multi-user support

---

# 📚 Learning Goals

This project demonstrates:

- Workflow automation
- API integrations
- AI model integration
- Self-hosting
- Reverse proxies
- Docker deployment
- SSL configuration
- Cloud hosting

---

# 🙌 Acknowledgements

- n8n
- Telegram
- OpenRouter
- Docker
- Caddy

---

# 📜 License

MIT License

---

# ⭐ Support

If you found this useful, give the repository a star ⭐
