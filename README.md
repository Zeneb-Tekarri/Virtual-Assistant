# Virtual-Assistant

### Project Description: Virtual Assistant "Shane"

**Objective:**
The project involves creating a virtual assistant named "Shane" that interacts with users through voice commands. The assistant is capable of performing a variety of tasks, including opening web browsers, checking the weather, performing mathematical operations, and more, all controlled via voice recognition.

**Key Features:**

1. **Voice Recognition:**
   - Utilizes the `speech_recognition` library to capture and recognize spoken commands from the user.
   - The assistant listens for a specific wake word ("Shane") to activate and then processes the subsequent commands.

2. **Text-to-Speech:**
   - Employs the `pyttsx3` library for converting text responses into speech, enabling the assistant to communicate back to the user.

3. **Web Browser Interaction:**
   - Uses the `webbrowser` module to open web pages based on user commands, such as searching for information online.

4. **Weather Information:**
   - Integrates with the OpenWeatherMap API (`pyowm` and `openweather`) to provide current weather updates when requested.

5. **Mathematical Operations:**
   - Capable of performing basic mathematical operations using the `operator` module.

6. **Randomized Responses:**
   - Uses the `random` module to provide varied responses, enhancing the interactive experience.

7. **File and Directory Management:**
   - Can interact with the computer's file system using the `os` module, allowing for tasks like opening specific files or folders.

8. **Persistent Logging:**
   - Maintains a conversation log (`Conversation Log.txt`) to store user commands for future reference and analysis.

9. **Error Handling:**
   - Implements error handling for common issues such as network errors, recognition errors, and command timeouts to ensure smooth operation.

**Technical Components:**
- **Speech Recognition Constants:**
  - `recognizer` and `microphone` are initialized for capturing and recognizing speech.
- **Text-to-Speech Configuration:**
  - The `pyttsx3` engine is configured for voice output with volume settings.
- **Wake Word Detection:**
  - The assistant listens for the wake word "Shane" to initiate further command processing.
- **Command Analysis:**
  - The assistant analyzes user commands to determine the appropriate action, whether it's a web search, opening a file, or providing information.

**Usage:**
The virtual assistant continuously listens for the wake word, after which it processes and responds to the user's commands. It can perform various tasks and provide information dynamically based on voice input.

This project demonstrates the integration of voice recognition, text-to-speech, API interaction, and basic task automation to create an interactive virtual assistant.
