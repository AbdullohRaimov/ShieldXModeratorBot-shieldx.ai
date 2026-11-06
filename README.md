# 🛡️ ShieldX — AI Telegram Security Bot

**ShieldX** is an intelligent Telegram bot designed to protect communities, moderate groups, and provide AI-powered assistance.

It combines automated moderation, AI chat assistance, file security scanning, and powerful administration tools in one platform.

## ✨ Features

### 🤖 AI Assistant
- AI-powered conversations using Ollama.
- Uzbek, Russian, and English language support.
- Normal Mode and Thinking Mode (development).
- Private chat AI assistant.
- Group AI assistance.

### 🛡️ Group Protection
- Anti-Spam protection.
- Anti-Flood protection.
- Duplicate message detection.
- Warning system.
- Mute, unmute, ban, unban, and kick commands.
- Configurable group moderation settings.

### 🔐 Security Scanner
- File security scanning through VirusTotal integration.
- Suspicious URL detection.
- SHA-256 file hash identification.
- Security reports.

### 👑 Admin Tools
- Group management.
- Moderation controls.
- Security settings.
- Group activity logs.
- Permission-based command access.

### 💎 Premium Tools
- Advanced AI capabilities.
- Thinking AI mode.
- Extended AI conversation features.
- Additional premium functionality.

*Premium payment integration and subscription management are under development.*

## 🌍 Supported Languages

- 🇺🇿 Uzbek
- 🇷🇺 Russian
- 🇬🇧 English

## ⚙️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| aiogram 3 | Telegram Bot API |
| Ollama | Local AI inference |
| Qwen 3.5 4B | AI model |
| SQLAlchemy | Database management |
| SQLite | Local database |
| VirusTotal API | File and URL security analysis |
| FastAPI | Web administration API |

## 🚀 Installation

### Requirements
- Python 3.14 or compatible version
- Ollama
- Telegram Bot Token
- Internet connection
- VirusTotal API key (for security scanning)

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

### 2. Create virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```cmd
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment

Copy `.env.example` to `.env` and configure your credentials.

Never publish your `.env` file.

### 5. Configure Ollama

Install Ollama and download the model:

```bash
ollama pull qwen3.5:4b-q4_K_M
```

Configure your `.env`:

```env
AI_PROVIDER=ollama
OLLAMA_BASE_URL=http://localhost:11434
OLLAMA_MODEL=qwen3.5:4b-q4_K_M
```

### 6. Start ShieldX

On Windows:

```cmd
3_bot_ishga_tushirish.bat
```

## 📋 Basic Commands

| Command | Description |
|---|---|
| `/start` | Start ShieldX |
| `/help` | Display help |
| `/rules` | Show group rules |
| `/report` | Report a problem |
| `/rep` | View reputation |
| `/secretary on` | Enable AI assistant |

Additional moderation commands require appropriate permissions.

## 🔒 Security

- Keep API keys and bot tokens private.
- Never upload `.env` or database files.
- Use permission checks for moderation commands.
- Do not expose the Ollama API directly to the public internet.
- Review VirusTotal results before taking moderation actions.

## 🗺️ Roadmap

- [x] Telegram bot foundation
- [x] AI integration with Ollama
- [x] Multilingual AI support
- [x] Group moderation
- [x] VirusTotal integration
- [ ] Unified User / Admin / Premium permission system
- [ ] Private chat administration
- [ ] Normal and Thinking AI modes
- [ ] Premium subscription payments
- [ ] Advanced security dashboard
- [ ] VPS deployment for 24/7 operation

## 👨‍💻 Project

**ShieldX — Intelligent Protection. Smarter Communities.**

A project focused on making Telegram communities safer through artificial intelligence and automated security.

---

**License:** To be determined.

**Status:** Active Development 🚧
