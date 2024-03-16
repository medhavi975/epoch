1. Installed the necessary libraries speech recognition and pydub which is used for speech recognition and audio-processing in subsequent code

2. Import pydub for audio file manipulation and audio segment for conversion.
   Used function 'CONVERT_TO_WAV' which takes mp3 file path as input, it reads the file using audio segment and then exports it to the WAV file.
3. The function def transcribe_large_audio('path'); transcribes large audio files by splitting them into smaller chunks based on silence, then applying Speech Recognition on each chunk.
4. After installing IBM Watson SDK, we imported the necessary modules.
   Code mounts Google Drive to the specified directory which allows access to files stored in Google Drive.
5. Text translation which translates Text obtained from speech into another language using IBM Watson language translator service.
6. Text-to-Speech Conversion: Using GTTS
7. Converted Speech into different languages.
