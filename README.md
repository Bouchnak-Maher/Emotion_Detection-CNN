# Emotion_Detection-CNN
Real-time face detection and emotion classification using a keras CNN model and openCV.


- Emotion Detection
Humans are used to non verbal communication. The emotions expressed increases the clarity of any thoughts and ideas. It becoms quite interesting when a computer can capture this complex feature of humans, ie emotions. This topic talks about building a model which can detect an emotion from an image. There key points to be followed are:

Data gathering and augmentation

The dataset taken was [ pull nategreb/emotion-detection.](https://www.kaggle.com/code/nategreb/emotion-detection/input).

Model building

The model architecture consists of CNN Layer, Max Pooling, Flatten and Dropout Layers.

Training

The model was trained by using variants of above layers mentioned in model building and by varying hyperparameters. The best model was able to achieve 60.1% of validation accuracy.

Testing

The model was tested with sample images. It can be seen below:

The model will be able to detect 7 types of emotions:-
Angry , Sad , Neutral , Disgust , Surprise , Fear , and Happy
Usage:
For Face Detection, and Emotion Detection Code
Refer to the notebook /Emotion_Detection.ipynb.
I have trained an emotion detection model and put its trained weights at /Models

Train your Emotion Detection Model
To train your own emotion detection model, Refer to the notebook /facial_emotion_recognition.ipynb

For Emotion Detection using Webcam
Clone the repo:
Run pip install -r requirements.txt
 python Emotion_Detection.py
