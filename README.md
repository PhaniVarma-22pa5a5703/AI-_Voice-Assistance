# AI Voice Assistant

## Overview
This project is an AI-powered voice assistant that can perform various tasks, including answering user queries using OpenAI, providing the current time and date, taking screenshots, and recognizing voice commands. The assistant integrates **speech recognition, text-to-speech conversion, and chatbot functionalities** using multiple Python libraries.

## Features
- **Voice Commands**: Listens and responds to user input via speech recognition.
- **Text-to-Speech (TTS)**: Converts AI responses into speech.
- **Chatbot Integration**: Communicates with OpenAI through the Eden AI API.
- **Time and Date Retrieval**: Provides the current time and date.
- **Screenshot Capture**: Takes screenshots upon voice command.
- **User-Friendly Interaction**: Greets users and offers assistance based on input.

## Technologies Used
- **Python**
- **pyttsx3** (Text-to-Speech)
- **SpeechRecognition** (Speech input processing)
- **pyscreeze** (Screenshot capturing)
- **requests** (API requests to Eden AI)
- **OpenAI API** (Chatbot functionality)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-voice-assistant.git
   cd ai-voice-assistant
   ```
2. Install dependencies:
   ```bash
   pip install pyttsx3 SpeechRecognition pyscreeze pillow requests openai
   ```
3. Run the program:
   ```bash
   python ai_assistant.py
   ```

## Usage
1. **Launch the program**.
2. The assistant will greet you and ask how it can assist you.
3. Give voice commands such as:
   - "What time is it?"
   - "What's today's date?"
   - "Take a screenshot."
   - "Tell me about AI."
4. Say **"exit"** to stop the assistant.

## Screenshots
(Add relevant screenshots here)

## License
This project is open-source and available under the **MIT License**.

## Author
Developed by **[Your Name]**.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Acknowledgments
- OpenAI API for chatbot responses.
- SpeechRecognition for voice input.
- pyttsx3 for text-to-speech conversion.

