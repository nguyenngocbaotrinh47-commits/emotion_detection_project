# Emotion Detection System

## Project Overview
This is a final capstone project for the "Python Project for AI & Application Development" course. The application uses **IBM Watson NLP** to analyze text and detect emotions such as anger, disgust, fear, joy, and sadness. It is deployed as a web application using the **Flask** framework.

## Project Structure
- `EmotionDetection/`: A Python package containing the logic for calling the Watson NLP API.
  - `emotion_detection.py`: Contains the `emotion_detector` function.
  - `__init__.py`: Makes the directory a package.
- `server.py`: The Flask server that handles web requests and renders the user interface.
- `test_emotion_detection.py`: Unit tests to ensure the emotion detection logic is accurate.
- `static/`: Contains CSS and JavaScript for the frontend.
- `templates/`: Contains the `index.html` file for the web UI.

## Features
- **Emotion Analysis**: Detects multiple emotions from a given string.
- **Dominant Emotion**: Identifies the strongest emotion in the text.
- **Error Handling**: Gracefully handles blank inputs and invalid requests (Status Code 400).
- **Unit Testing**: Verified logic through Python's `unittest` library.
- **Static Code Analysis**: Compliant with `pylint` standards for clean and readable code.
