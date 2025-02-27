# SpeechRec
A simple voice translation application that recognizes speech, translates it into a selected language, and converts the translated text into speech.

## Features
- Speech recognition using `speech_recognition` library.
- Translation using `translate` library.
- Text-to-speech conversion using `gTTS`.
- Simple GUI input using `tkinter` for selecting languages and user interaction.
- Plays translated speech using `pygame`.

## Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required libraries:
  ```bash
  pip install speechrecognition translate gtts pygame tkinter
  ```

## Installation
1. Clone the repository:
   ```bash
   git clone https://syar-kota/speechREC.git
   cd your-repo
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   SpeecREC.py
   ```

## Usage
1. The application will prompt you to enter the source and destination languages (e.g., `en` for English, `fr` for French).
2. After confirming, you will be prompted to speak.
3. The recognized speech will be translated and converted to speech in the target language.
4. You can choose to translate another phrase, change languages, or exit.

## Supported Languages
The application supports all languages available in Google Translate and Google Text-to-Speech (`gTTS`). Use language codes (e.g., `en` for English, `es` for Spanish, `hi` for Hindi).

## Known Issues
- Background noise may affect speech recognition accuracy.
- The translation library may not support all phrases correctly.
- `gTTS` requires an internet connection.

## License
This project is licensed under the MIT License.


---
Feel free to contribute and improve the project!

