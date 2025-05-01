# Kinya Voice Assistant 🎙️

A smart, conversational voice assistant for Kinyarwanda speakers

Kinya is a cutting-edge voice assistant designed to understand and respond naturally in Kinyarwanda. Powered by advanced speech recognition and synthesis, it bridges the gap between users and technology through seamless voice interactions.

## ✨ Key Features

- 🗣️ **Native Kinyarwanda Support** – Built specifically for Rwandan language and accents
- 🎙️ **Speech-to-Text** – Accurate voice transcription using NeMo AI models
- 🧠 **Smart Responses** – Combines rule-based logic + ChatGPT for natural conversations
- 🔊 **Text-to-Speech** – Fluent Kinyarwanda audio output with MB-iSTFT-VITS2
- 🌐 **Web Interface** – Easy-to-use Gradio UI for instant testing

## 🏁 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/BYUMVUHOREAimable/kinyarwanda-voice-assistant.git
```

2. Install dependencies (see Setup Guide below)
3. Launch the Gradio interface to start chatting!

## 🔍 How It Works

Kinya processes conversations in 3 steps:

1. **Listen** → Converts speech to text (STT)
2. **Understand** → Analyzes queries with hybrid NLP
3. **Respond** → Generates spoken replies (TTS)

## ⚙️ Tech Stack

### Speech Recognition
- **Framework**: NVIDIA NeMo
- **Model**: Pretrained Kinyarwanda STT from [RW-DEEPSPEECH-API](https://github.com/agent87/RW-DEEPSPEECH-API/tree/main/stt)
- **Input**: Handles mic/web audio with noise reduction

### Natural Language Processing
**Hybrid Engine**:
- Rule-based patterns for common phrases
- ChatGPT integration for complex questions
- Custom intent detection

### Voice Synthesis
- **Model**: [KinyaTTS](https://github.com/anzeyimana/KinyaTTS) (MB-iSTFT-VITS2)
- **Output**: Natural-sounding Kinyarwanda speech

## 📦 Installation

### Prerequisites
- Python 3.8+
- NVIDIA GPU (recommended)
- Google Colab (for notebook)

### Dependencies
```bash
pip install -e /path/to/Inference/  # KinyaTTS
pip install "numpy<2.1.0,>1.26.0" Cython gradio openai
```

## 🚨 Current Limitations

- **Audio Quality**: Works best in quiet environments
- **Language Detection**: May confuse similar Bantu languages
- **Sampling Rates**: Requires specific audio formats (16kHz recommended)

## 📚 Resources

- [TTS Model (Google Drive)](https://drive.google.com/drive/folders/1vrecoCWw_XQjIZt4LX4h7FbTK_Bk7Qw3)
- [Demo Notebook](kin_assistant.ipynb)

## 🙏 Credits & Acknowledgments

- **STT Model**: [RW-DEEPSPEECH-API](https://github.com/agent87/RW-DEEPSPEECH-API)
- **TTS Research**: Rwanda MIT Team ([KinyaTTS](https://github.com/anzeyimana/KinyaTTS))
- **AI Partner**: [OpenAI's ChatGPT](https://openai.com/chatgpt)

## 📜 License

BYUMVUHOREAimable License – Open source and free to use!

---
Built with love for All AI ecosystem

---
Happy coding & learning!