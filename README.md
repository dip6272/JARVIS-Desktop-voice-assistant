# JARVIS Desktop Voice Assistant

JARVIS is a desktop voice assistant that can perform various tasks based on voice commands. It can search Wikipedia, tell the time and date, open websites and applications, play music, and more.

## Features

1. **Wikipedia Search**: Search for information on Wikipedia.
2. **Time and Date**: Get the current time and date.
3. **Chat Queries**: Respond to greetings and other simple queries.
4. **Open Websites**: Open popular websites like YouTube, Google, Instagram, StackOverflow, etc.
5. **Open Applications**: Open applications like Chrome, Edge, WhatsApp, Calculator, Notepad, etc.
6. **Start Any App**: Start any application that exists on the laptop.
7. **Play Music**: Play random music from a specified directory.
8. **Voice Commands**: Use voice commands to interact with JARVIS.
9. **Shortcut Key for Speak**: Press `Ctrl+Q` to trigger the speak function.

## Commands

Refer to the [command.txt](command.txt) file for a list of supported commands.

## Installation

1. Clone the repository.
2. Install the required packages using `pip`:
    ```sh
    pip install pyttsx3 speechRecognition wikipedia pyautogui
    ```

## Usage

1. Run the `jarvis.py` script:
    ```sh
    python jarvis.py
    ```
2. Use the GUI to interact with JARVIS. You can type queries or use the `Speak` button to give voice commands.

## Screenshots

![JARVIS Assistant](images/jarvis_assistant.png)

## License

This project is licensed under the MIT License.