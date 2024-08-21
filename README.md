#  VoiceAssistant

voice-activated desktop assistant that performs various tasks like searching Wikipedia, opening websites, and launching applications based on voice commands. It is developed using Python with the integration of speech recognition and web automation libraries.

## Features

- **Voice Commands**: Interact with your desktop using voice commands.
- **Wikipedia Search**: Get quick summaries from Wikipedia.
- **Web Automation**: Open popular websites like YouTube, Google, GitHub, and more with simple voice prompts.
- **Application Launching**: Launch local applications like WhatsApp directly from your voice command.
- **File System Navigation**: Open local disk drives through voice commands.

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Judinus10/voiceAssistant.git
   ```
2. **Install Required Packages:**
   ```bash
   pip install pyttsx3 speechrecognition wikipedia-api
   ```
3. **Run the Application:**
   ```bash
   python VA.py
   ```

## How to Use

1. Run the script using the command provided above.
2. The assistant will greet you and ask how it can help.
3. Provide your command, such as "open YouTube" or "search Wikipedia for Python."
4. The assistant will perform the task and respond accordingly.

## Customization

- **Voice Settings**: You can customize the assistant's voice by modifying the `voices` property in the script.
- **Additional Commands**: Add more commands by expanding the `if-elif` blocks in the script.

## Technologies Used

- **Python**
- **Pyttsx3**: Text-to-speech conversion
- **SpeechRecognition**: Convert speech to text
- **Wikipedia API**: Fetch summaries from Wikipedia
- **Webbrowser Module**: Automate web browser actions
- **OS Module**: Launch local applications

## Contributing

Feel free to contribute to this project by submitting a pull request or reporting any issues.

## License

This project is licensed under the MIT License.

---

This README provides a clear overview of the project, instructions for setup, and details on how to use and customize the assistant.