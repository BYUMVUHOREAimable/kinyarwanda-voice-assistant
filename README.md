🗣️ Kinyarwanda Voice Assistant
An intelligent and culturally inclusive voice assistant designed to understand and communicate in Kinyarwanda—bridging the language gap in AI through real-time speech recognition and synthesis.

🚀 Get Started
To start using the Kinyarwanda Voice Assistant, clone the repository:

git clone https://github.com/BYUMVUHOREAimable/kinyarwanda-voice-assistant.git
✨ Key Highlights
🎙️ Voice Recognition: Captures and transcribes Kinyarwanda speech using deep learning models

🤖 Query Interpretation: Understands user input with rule-based NLP and ChatGPT integration

🗣️ Voice Output: Responds in fluent, human-like Kinyarwanda using MB-iSTFT-VITS2

🖥️ Gradio Interface: Simple, clean UI for voice interaction via browser

🧠 How It Works
The assistant performs three major functions:

Speech-to-Text (STT): Uses NVIDIA NeMo and custom-trained models to convert voice into text

Natural Language Processing: Interprets queries through hybrid logic and AI

Text-to-Speech (TTS): Synthesizes natural-sounding Kinyarwanda responses

🧪 Demonstrations

Terminal	Interface	Voice Flow
		
🏗️ Architecture Breakdown
🎧 STT: Voice to Text
Built on NeMo

Enhanced with RW-DEEPSPEECH-API

🧩 NLP: Understanding You
Rule-based query handling

ChatGPT API for broader context understanding

Intent classification and command routing

🔊 TTS: Text to Voice
Powered by KinyaTTS and MB-iSTFT-VITS2

Outputs lifelike Kinyarwanda responses

⚙️ Installation Guide
📋 Requirements
Python 3.x

CUDA-enabled GPU (preferred)

Google Colab (optional for testing)

📦 Install Dependencies
bash
Copy
Edit
pip install -e /path/to/Inference/
pip install "numpy<2.1.0,>1.26.0"
pip install Cython gradio openai
🧰 Usage Instructions
Open kin_assistant.ipynb in Google Colab

Mount your Google Drive (with model files)

Run the notebook cells step by step

Interact using the Gradio interface

⚠️ Known Limitations
Works best in noise-free environments

May occasionally misidentify similar-sounding languages (e.g., Swahili)

Requires correct sampling rate for audio input

📚 Resources
🔗 Full Source + TTS Models (Google Drive)

📓 Project Notebook: kin_assistant.ipynb

🙌 Acknowledgments
NVIDIA NeMo for STT foundation

KinyaTTS by Rwanda MIT researchers

OpenAI ChatGPT for intelligent dialogue

Google Colab as the development environment

📜 License
Distributed under the MIT License. Feel free to use, modify, and share!

Built with pride for the people of Rwanda 🇷🇼
Enabling inclusive AI, one voice at a time.