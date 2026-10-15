# Final Project

## Emotion Detection Application using Watson NLP

Final project of the course "Developing AI Applications with Python and Flask" (IBM).

An emotion detection web application built with Python, Flask and the Watson NLP EmotionPredict function. Given a text, it returns the scores for anger, disgust, fear, joy and sadness, along with the dominant emotion.

### Project structure

- `EmotionDetection/` - package with the `emotion_detector` function
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask web server (runs on `localhost:5000`)
- `templates/index.html` and `static/mywebscript.js` - web interface

### Run

```bash
python3 server.py
```
