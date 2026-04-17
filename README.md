# ClickUi - www.ClickUi.app

ClickUi is a powerful, cross-platform AI assistant built in pure Python. It integrates voice interaction, text chat, web search, and property lookups into a seamless desktop experience.

<div align="center">

![prompot](https://github.com/user-attachments/assets/b1feb373-ae54-4274-9fd0-2c1b2e30926d)

![Python](https://img.shields.io/badge/100%25-Python-blue) 
![STT](https://img.shields.io/badge/STT-Whisper-red)
![TTS](https://img.shields.io/badge/TTS-Kokoro-purple)
![GUI](https://img.shields.io/badge/GUI-PySide6-cyan)
![Models](https://img.shields.io/badge/Models-Ollama%20|%20OpenAI%20|%20Google%20|%20Claude-orchid)

</div>

---

## 🚀 Features

- **Voice Mode:** Talk to your AI using Whisper (STT) and Kokoro (TTS).
- **Chat Mode:** Modern text-based interface for deep interactions.
- **Multi-Model Support:** Connect to OpenAI, Google (Gemini), Claude, Ollama, Groq, and OpenRouter.
- **Web Search:** Real-time information retrieval via Google Search (Playwright/Selenium).
- **Property Lookups:** Instant estimates from Zillow and Redfin.
- **File Attachments:** Drop files directly into the chat for analysis.
- **Conversation History:** Local history management for persistent context.

---

## 🛠️ Quick Start (Windows)

1. **Install Conda:** Download from [anaconda.com](https://www.anaconda.com/).
2. **Run Install.bat:** Simply run `Install.bat` to automate the setup and launch.
3. **Launch:** Press `Ctrl+k` (default hotkey) to toggle the UI once it's ready.

---

## 💻 Manual Installation

```bash
# 1. Create environment
conda create --name click_ui --file conda_packages.txt
conda activate click_ui

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run
python clickui.py
```

---

## ⚙️ Configuration

Edit `.voiceconfig` or use the in-app **Settings** menu to manage:
- API Keys (OpenAI, Google, etc.)
- Preferred Model Engine
- Browser settings for Web Search
- Hotkeys and UI preferences

---

## 🚧 Future Roadmap

- [ ] Interruptible TTS playback (speak to interrupt).
- [ ] Code block formatting with copy-to-clipboard.
- [ ] Keyboard-navigable UI.
- [ ] Selectable area screenshots for visual context.
- [ ] Multi-file attachment support.
- [ ] Browser-use integration for web automation.

---

## 🤝 Contributing

Looking for collaborators! Submit pull requests to `main`. Check the issues or future features list to see where you can help.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=CodeUpdaterBot/ClickUi&type=Date)](https://www.star-history.com/#CodeUpdaterBot/ClickUi&Date)
