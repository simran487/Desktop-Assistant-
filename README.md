# Desktop-Assistant-

# Peghie: The Desktop Assistant

**Peghie** is a Python-based desktop assistant that uses voice commands to perform various tasks. It leverages libraries like `pyttsx3` for text-to-speech, `speech_recognition` for voice input, and `pywhatkit` for web interactions. This assistant can perform functions such as searching Wikipedia, opening websites, playing music, and sending emails.

## Features

- **Voice Commands**: Interact with the assistant using voice commands.
- **Wikipedia Search**: Search Wikipedia and get summaries of topics.
- **Open Websites**: Open popular websites like YouTube, Google, Stack Overflow, and more.
- **Play Music**: Play a specific music file from a predefined directory.
- **Send Emails**: Send emails to predefined recipients.
- **System Operations**: Open applications like Visual Studio Code.

## Libraries Used

- `pyttsx3`: Text-to-speech conversion library.
- `speech_recognition`: Recognizes speech and converts it into text.
- `datetime`: Handles date and time operations.
- `wikipedia`: Retrieves Wikipedia summaries.
- `webbrowser`: Opens web pages.
- `os`: Provides a way to interact with the operating system.
- `smtplib`: Handles sending emails.
- `pywhatkit`: Provides various functionalities, including playing YouTube videos.

## Setup

1. **Install Dependencies**: Make sure you have Python installed and then install the required libraries using pip:
    ```bash
    pip install pyttsx3 speech_recognition wikipedia pywhatkit
    ```

2. **Email Configuration**: Update the `sendEmail` function with your Gmail credentials and modify the recipient's email address as needed.

3. **Music Directory**: Update the `music_dir` variable with the path to your music file.

4. **Code Path**: Update the `codePath` variable with the path to Visual Studio Code or any other application you want to open.

## Usage

1. **Run the Script**: Execute the script using Python:
    ```bash
    python peghie.py
    ```

2. **Voice Commands**: Use voice commands to interact with the assistant. For example:
   - "Wikipedia [topic]" to search Wikipedia.
   - "Open YouTube" to search and play a YouTube video.
   - "Play music" to play a music file.
   - "Email to [name]" to send an email.

## Note

- Ensure that you have a working microphone and an active internet connection for voice commands and web-based functionalities.
- Modify the paths and email credentials in the script according to your setup.

## Contributing

Feel free to contribute by submitting issues or pull requests. Your feedback and contributions are highly appreciated!

## License

This project is licensed under the MIT License.

