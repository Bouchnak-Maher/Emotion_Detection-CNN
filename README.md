# Emotion_Detection-CNN
Real-time face detection and emotion classification using a keras CNN model and openCV.


- Emotion Detection
Humans are used to non verbal communication. The emotions expressed increases the clarity of any thoughts and ideas. It becoms quite interesting when a computer can capture this complex feature of humans, ie emotions. This topic talks about building a model which can detect an emotion from an image. There key points to be followed are:

- Data gathering and augmentation

The dataset taken was [ pull nategreb/emotion-detection.](https://www.kaggle.com/code/nategreb/emotion-detection/input).

- Model building

The model architecture consists of CNN Layer, Max Pooling, Flatten and Dropout Layers.

- Training

The model was trained by using variants of above layers mentioned in model building and by varying hyperparameters. The best model was able to achieve 60.1% of validation accuracy.

- Testing

The model was tested with sample images.

The model will be able to detect 7 types of emotions:
- Angry:

![angry](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/62b1152e-0317-4a29-83b0-dc5a199397a2)

- Sad : 
 
 ![sad](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/bd2549dd-394f-4dc2-bde5-c198ed734995)


- Surprise:

![surprise](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/7bfee8a8-3f49-4c97-a172-f9f674fe1041)

- Happy:

![detectedimg](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/71b6a316-3d2a-4216-a373-f80cf2a85ba9)

- Neutral :
 
 

-    , Disgust ,  , Fear , and 
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
