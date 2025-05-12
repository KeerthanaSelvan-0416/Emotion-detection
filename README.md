# Emotion Detection from Facial Expressions Using Deep Learning

This project utilizes a pre-trained emotion detection model (Mini-XCEPTION) to detect emotions from facial expressions in images. The model classifies emotions such as Angry, Happy, Sad, Fear, Surprise, Neutral, and Disgust by detecting faces in the image and predicting the corresponding emotion.

## Features
- Detects and classifies emotions from facial expressions.
- Identifies multiple faces in an image.
- Uses a pre-trained Mini-XCEPTION model for emotion recognition.
- Displays the result by drawing bounding boxes around faces and labeling them with the predicted emotion.

## Requirements

The following Python packages are required to run the project:

- `keras`
- `opencv-python`
- `numpy`
- `google.colab` (Only for Google Colab environment)

You can install the necessary dependencies by running:

```bash
pip install -q keras opencv-python
