# Emotion Detection Application

A web-based application built using Python, Flask, and IBM Watson NLP Embeddable AI library for emotion detection and sentiment analysis.

## Project Description
This project develops an Emotion Detection system that analyzes text input to determine emotional content across five categories:
- **Anger**
- **Disgust**
- **Fear**
- **Joy**
- **Sadness**

It also identifies the **Dominant Emotion** with the highest confidence score. The application is deployed as a lightweight web service using the Flask framework.

## Project Structure
- `EmotionDetection/`: Python package containing the core Watson NLP emotion detector logic.
  - `__init__.py`: Package initialization exposing the `emotion_detector` function.
  - `emotion_detection.py`: Core function interacting with the Watson NLP API.
- `server.py`: Flask web server routing user requests and delivering analysis responses.
- `test_emotion_detection.py`: Unit tests validating emotion detection accuracy.
- `static/`: Static JavaScript and styling assets for the web UI.
- `templates/`: HTML templates for the frontend interface.

## Author
Priyal Khunia
