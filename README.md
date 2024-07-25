# Virtual Assistant 
### Project Description: Virtual Assistant "Hanna"

**Objective:**
The project involves creating a virtual assistant named "Hanna" that interacts with users through voice commands. Hanna can play music, tell the time, provide information from Wikipedia, and even tell jokes, enhancing user experience through voice interaction.

**Key Features:**

1. **Voice Recognition:**
   - Utilizes the `speech_recognition` library to capture and recognize spoken commands from the user.
   - The assistant listens for its wake word "Hanna" to activate and then processes the subsequent commands.

2. **Text-to-Speech:**
   - Employs the `pyttsx3` library for converting text responses into speech, enabling the assistant to communicate back to the user.
   - Configured to use a female voice.

3. **Music Playback:**
   - Integrates with `pywhatkit` to play songs on YouTube based on user commands.

4. **Time Telling:**
   - Uses the `datetime` module to provide the current time when requested.

5. **Wikipedia Integration:**
   - Uses the `wikipedia` library to fetch and summarize information about people or topics when asked "who is" followed by the name of the person or topic.

6. **Jokes:**
   - Uses the `pyjokes` library to tell jokes when requested by the user.

7. **Conversational Responses:**
   - Provides humorous or conversational responses to questions like "are you single" or "date".

**Technical Components:**

- **Speech Recognition Constants:**
  - `listener` is initialized to capture and recognize speech.
- **Text-to-Speech Configuration:**
  - The `pyttsx3` engine is configured for voice output with a female voice setting.
- **Wake Word Detection:**
  - The assistant listens for the wake word "Hanna" to initiate further command processing.
- **Command Analysis:**
  - The assistant analyzes user commands to determine the appropriate action, whether it's playing a song, telling the time, providing information, or telling a joke.

**Functions:**

- `talk(text)`: Converts the given text to speech.
- `take_command()`: Listens for user commands, processes them, and returns the recognized command.
- `run_hanna()`: Main function that interprets commands and triggers the appropriate actions based on the user's request.

**Usage:**
The virtual assistant continuously listens for its wake word. Upon recognizing the wake word "Hanna," it processes and responds to user commands, such as playing music, telling the time, providing information, or telling jokes. The assistant operates in a loop, constantly waiting for user interaction.

This project showcases the integration of voice recognition, text-to-speech, online information retrieval, and entertainment features to create an interactive and engaging virtual assistant.
