# IJCMWANZA Court Voice Translator

A voice translator application that converts spoken language to text, translates the text to a desired language, and then plays the translated text using text-to-speech. This project uses Python's `speech_recognition` for voice recognition, `translate` for text translation, `gTTS` for text-to-speech, and `pygame` for audio playback. The graphical interface is handled by `tkinter`.

## Features

- Recognizes spoken language and converts it to text.
- Translates text to a specified target language.
- Converts translated text to speech and plays it back.
- Allows users to choose source and target languages dynamically.
- Simple and interactive GUI for ease of use.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Atupakisyestephen/IJCMWANZA_Court_Voice_Translator.git
   cd IJCMWANZA_Court_Voice_Translator

2. Install the required Python packages:
   ```bash
   pip install SpeechRecognition translate gTTS pygame

3. Ensure you have tkinter installed (it’s included by default with Python on most systems).

## Usage
1. Run the application:
   ```bash
   python voice_translator.py
2. Follow the prompts to set your source and destination languages (e.g., en for English, fr for French).
3. Speak into the microphone when prompted, and the application will translate and play back your speech in the target language.

## Requirements
- Python 3.x
- speech_recognition – For voice recognition
- translate – For translating text
- gTTS – For converting text to speech
- pygame – For audio playback
- tkinter – For GUI interface

## Example
After starting the application, set the source language to en (English) and the target language to fr (French). Speak a phrase like "Hello, how are you?" The app will translate it to "Bonjour, comment ça va ?" and play it back in French.

## Error Handling
- If the app can’t recognize your voice, it will display "Sorry, I could not understand your audio."
- Translation and text-to-speech errors are handled with appropriate messages.

## Contact
For questions or support, feel free to reach out:</br>
Name: Atupakisye S. Elias</br>
Phone: 0626561774, 0656915449</br>
LinkedIn: linkedin.com/in/atupakisye</br>
YouTube Channel: youtube.com/@AtupakisyeElias</br>
Personal Website: atupakisyestephen.github.io/My-Personal-Website/

## License
This project is licensed under the MIT License.

## Acknowledgments
- Google Speech Recognition for voice recognition
- Google Text-to-Speech for converting text to speech
- Pygame for audio playback

