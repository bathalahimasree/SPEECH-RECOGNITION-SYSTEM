# SPEECH-RECOGNITION-SYSTEM
COMPANY : CODTECH IT SOLUTIONS

NAME : BATHALA HIMASREE

INTERN ID :CT06DG1957

DOMAIN : ARTIFICIAL INTELLIGENCE

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH
** DESCRIPTION OF TASK 2:


Task 2 focused on developing a basic Speech-to-Text (STT) system using Python libraries. The goal was to convert an audio file (spoken content) into readable and editable text. I performed this task in Jupyter Notebook using Python kernel, and used the SpeechRecognition and pydub libraries to complete it. This task is an example of Automatic Speech Recognition (ASR), which is used in many voice-driven applications.

The first step was handling the audio file. My input file was in .mp3 format, which is not directly supported by the SpeechRecognition library. To fix this, I used the pydub library to convert the .mp3 file into .wav format, which is supported. This required installing ffmpeg or using an online converter. Once the audio was converted, I loaded it using sr.AudioFile() and passed it through the recognizer.

The transcription process involved using the recognize_google() method from the recognizer object. This uses Google’s Web Speech API to convert speech into text. After transcription, the output was printed in the notebook. The tool worked accurately for clear audio, and the final result was a properly formatted paragraph based on spoken content.

Speech-to-text technology has several important applications. In virtual assistants like Siri, Google Assistant, and Alexa, this technology powers the voice input and command system. In call centers, audio logs are transcribed and analyzed for quality assurance and sentiment analysis. In healthcare, doctors use STT tools to dictate notes that get converted into text for patient records. It is also useful for journalists, students, and professionals who need to convert meeting recordings, interviews, or lectures into text.

This task also introduced me to real-world challenges in audio processing. Audio clarity, speaker accents, background noise, and file compatibility can all affect transcription accuracy. I also learned how to implement error handling in Python to catch common issues such as unintelligible audio or poor network response from the API.

Tools and technologies used:

Python

Jupyter Notebook

SpeechRecognition library for transcription

Pydub library for audio conversion

Google Speech API (used internally by the recognizer)

Through this task, I gained experience working with multimedia input in AI applications. I now better understand how speech recognition models work and how to integrate them into real-time tools. More importantly, I learned how accessible it is to build a working prototype using open-source Python libraries.

To conclude, Task 2 gave me practical knowledge in a technology that is shaping the future of hands-free, voice-driven interfaces. It taught me the power of combining Python with simple yet robust libraries to perform meaningful audio processing tasks. This is a skill I can apply to future projects in accessibility, voice assistants, transcription tools, and smart applications.

OUTPUT:
<img width="393" height="118" alt="Image" src="https://github.com/user-attachments/assets/b998b165-5af4-45ca-9874-c5ab52f4c914" />
