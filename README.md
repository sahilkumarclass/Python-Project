# 🎤 Ankit A.I - Python Voice Assistant

A sophisticated Python-based voice assistant that combines speech recognition with OpenAI's GPT-3 to create an intelligent, conversational AI companion. Ankit A.I can understand voice commands, engage in natural conversations, and perform various system tasks seamlessly.

## ✨ Features

- **🗣️ Voice-to-Text Conversion**: Advanced speech recognition for natural voice interactions
- **🤖 AI-Powered Conversations**: Integration with OpenAI GPT-3 (text-davinci-003) for intelligent responses
- **🌐 Quick Web Access**: Instantly open popular websites with voice commands
- **🎵 Media Control**: Launch music applications and media players
- **📱 App Integration**: Open system applications like FaceTime and other utilities
- **⏰ Time Reporting**: Get current time information on demand
- **💾 Response Logging**: Automatically save AI conversations to text files
- **🔊 Voice Feedback**: System speech synthesis for audio responses
- **🔄 Chat Management**: Reset conversation history and clean exit options

## 🛠️ Requirements

### System Requirements
- **Python 3.x**
- **macOS** (optimized for macOS commands and applications)

### Python Dependencies
```bash
speech_recognition
openai
pyaudio  # Optional, for enhanced microphone input
```

### API Requirements
- **OpenAI API Key** (required for GPT-3 integration)

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone <repository-url>
cd ankit-ai-voice-assistant
```

### 2. Install Required Packages
```bash
pip install speechrecognition openai
```

### 3. Configure OpenAI API
Create a `config.py` file in the project root directory:
```python
# config.py
apikey = "your_openai_api_key_here"
```

### 4. Install Audio Dependencies (Optional)
For enhanced microphone support on macOS:
```bash
brew install portaudio
pip install pyaudio
```

## 🎯 Usage

### Starting the Assistant
```bash
python ankit_ai.py
```

### Voice Commands

| Command Category | Example Commands | Description |
|-----------------|------------------|-------------|
| **Web Navigation** | "Open YouTube", "Open Google", "Open Wikipedia" | Launch websites in default browser |
| **Media Control** | "Open music", "Play music" | Launch music applications |
| **Communication** | "Open FaceTime" | Start video calling apps |
| **Utilities** | "Open Passky", "Open pass" | Launch password manager |
| **Time Query** | "What's the time?", "Tell me the time" | Get current time |
| **AI Interaction** | "Using artificial intelligence", "AI chat" | Engage GPT-3 for conversations |
| **System Control** | "Reset chat" | Clear conversation history |
| **Exit** | "Jarvis quit", "Exit" | Terminate the assistant |

### Example Interaction
```
User: "Hello Ankit"
Ankit A.I: "Hello! How can I assist you today?"

User: "What's the weather like?"
Ankit A.I: [GPT-3 powered response about weather]

User: "Open YouTube"
Ankit A.I: "Opening YouTube..." [Launches YouTube in browser]
```

## 📁 Project Structure
```
ankit-ai-voice-assistant/
│
├── ankit_ai.py           # Main application script
├── config.py             # API configuration file
├── README.md             # Project documentation
└── chat_logs/            # Directory for saved conversations
    └── responses.txt     # AI conversation logs
```

## 🔧 Configuration

### OpenAI API Setup
1. Visit [OpenAI Platform](https://platform.openai.com/)
2. Create an account and generate an API key
3. Add your API key to `config.py`:
   ```python
   apikey = "sk-your-actual-api-key-here"
   ```

### Customizing Voice Commands
Modify the command recognition logic in the main script to add new voice commands or change existing ones.

## 🖥️ Platform Compatibility

**Primary Support**: macOS
- Uses `say` command for text-to-speech
- Uses `open` command for launching applications
- Optimized for macOS system integration

**Other Platforms**: Requires modification of system commands for Windows/Linux compatibility.

## 🐛 Troubleshooting

### Common Issues
- **Microphone not detected**: Install PyAudio and check microphone permissions
- **OpenAI API errors**: Verify API key is correct and account has sufficient credits
- **Speech recognition fails**: Check internet connection and microphone settings
- **Applications won't open**: Ensure correct application names for your system

### Debug Mode
Add logging to troubleshoot issues:
```python
import logging
logging.basicConfig(level=logging.DEBUG)
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **OpenAI** for providing the GPT-3 API
- **Python Speech Recognition** library contributors
- **Open source community** for inspiration and support

## 📧 Contact

**Developer**: Sahil

---

⭐ **Star this repository if you found it helpful!**
