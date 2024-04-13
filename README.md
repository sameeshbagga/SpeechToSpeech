
End-to-End Speech Translation Project
Description
This project focuses on developing an End-to-End Speech Translation system, facilitating seamless communication across languages. It employs various techniques and libraries for speech recognition, audio processing, transcription, translation, and text-to-speech conversion.

Installation
Install the necessary libraries:

SpeechRecognition
pydub
Ensure you have IBM Watson SDK installed for text translation and other related tasks.

Usage
Audio File Manipulation:

Import pydub for audio file manipulation.
Utilize the CONVERT_TO_WAV function to convert audio files to WAV format.
Transcribing Large Audio Files:

Use the transcribe_large_audio(path) function to transcribe large audio files.
This function splits audio files into smaller chunks based on silence and applies Speech Recognition to each chunk.
Google Drive Integration:

Mount Google Drive to a specified directory to access files stored in Google Drive.
Text Translation:

Translate text obtained from speech into another language using IBM Watson Language Translator service.
Text-to-Speech Conversion:

Utilize GTTS (Google Text-to-Speech) for converting text to speech.
Speech Translation:

Convert speech into different languages seamlessly.
Requirements
Python 3.x
SpeechRecognition
pydub
IBM Watson SDK
Google Text-to-Speech (GTTS)
Contributing
Feel free to contribute to this project by submitting pull requests or opening issues.
