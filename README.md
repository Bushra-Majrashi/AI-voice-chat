# AI-voice-chat
This project develops a simple speech-to-text chatbot using Python, Flask, and speech recognition. The application lets users interact with a chatbot by asking questions, which are eventually transcribed and processed to provide an audio response.
## Requirements
- Python (3.6+)
- Google Cloud Generative AI (for ask_gemini function)
  
 ### download these libraries:
- Flask
- pyttsx3
- google-generativeai

## Usage:

- Run the Flask application:
``Bash
python app.py``

- Open a web browser and navigate to http://localhost:5000.
- Click the "Start Listening" button to activate speech recognition.
- Speak your question. The transcribed text will appear in the text area.
- The chatbot will process the question and provide an audio response.

## How it works:

- The frontend (HTML, CSS, JavaScript) handles user interaction and speech recognition.
- The Flask backend receives the transcribed question from the frontend.
- The ask_gemini function sends the question to the Google Gemini model to generate a response.
- The response is rendered on the frontend and also spoken aloud using pyttsx3.

![Screenshot 2024-07-31 013730](https://github.com/user-attachments/assets/4d6fade9-9d0e-4d51-ae57-82fc38a449df)

