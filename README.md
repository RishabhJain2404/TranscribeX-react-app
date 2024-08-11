# TranscribeX

A React web based transcription & translation application that uses web workers to run ML models in the browser

![Screenshot (240)](https://github.com/user-attachments/assets/0c679d19-2fa2-4e3b-8491-776766f5f1d3)

This application leverages React for a user-friendly interface and incorporates web workers to offload computationally intensive machine learning models from the main thread. This approach ensures smooth performance and a responsive user experience while accurately transcribing audio content into text and translating the transcribed text into multiple languages.

# Breakdown:

- **React:** The application's frontend is built using React, providing a dynamic and interactive user interface.
- **Web Workers:** To optimize performance, computationally demanding ML models for transcription and translation are executed in web workers, separate threads that run in the background without interfering with the main UI thread.
- **Transcription:** The application can transcribe audio content into text in real time.
- **Translation:** The transcribed text can be translated into various languages, enhancing accessibility and global reach.
