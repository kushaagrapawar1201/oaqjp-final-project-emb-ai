# Emotion Detection Application

A web application developed using Python, Flask, and the Watson NLP Emotion Predict library. The application analyzes user input text and detects emotions such as anger, disgust, fear, joy, and sadness, identifying the dominant emotion.

## Project Structure
- `EmotionDetection/`: Package containing the emotion detection logic.
  - `__init__.py`: Package initialization importing `emotion_detector`.
  - `emotion_detection.py`: Watson NLP API call and response parsing with error handling.
- `server.py`: Flask web server serving the web interface and API endpoints.
- `test_emotion_detection.py`: Unit tests validating emotion detection accuracy.
- `templates/`: HTML templates for the frontend.
- `static/`: Static JavaScript and CSS files.

## Features
- Watson NLP Emotion Detection integration.
- Formatted emotion scores and dominant emotion extraction.
- Flask web interface running on port 5000.
- Error handling for invalid/blank inputs (HTTP status 400 handling).
- Unit tests with `unittest`.
- 10.00/10 Pylint static code analysis compliance.
