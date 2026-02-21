# 🦞 OpenClaw Direct

Welcome to the demo! Follow these steps to get your AI agent live in minutes.

### 🚀 Quick Start

1. **Prepare your Keys**: 
   - Rename `.env.example` to `.env`.
   - Paste your **Gemini API Key** and **Telegram Bot Token** into the file and save it.

2. **Launch the Environment**:
   - Click the **Open in GitHub Codespaces** button.
   - Wait for the terminal to finish the automatic installation (approx. 2 minutes).

3. **First-Time Setup**:
   - If this is your first run, type this command to link your keys:
     ```bash
     export $(grep -v '^#' .env | xargs) && openclaw onboard
     ```
   - **Tip**: When the wizard asks for a key, just hit **[Enter]**—it will pull the value from your `.env` automatically!

4. **Ignite the Bot**:
   - Start the engine by typing:
     ```bash
     openclaw gateway run
     ```
   - Message your bot on Telegram to say hello!

---

### 🔄 Returning Later?
Your data is persistent. Every time you restart this Codespace, the bot will now **automatically start** in the background using your saved `.env` and settings.
