# Emotion_Detection-CNN
Real-time face detection and emotion classification using a keras CNN model and openCV.


- Emotion Detection
Humans are used to non verbal communication. The emotions expressed increases the clarity of any thoughts and ideas. It becoms quite interesting when a computer can capture this complex feature of humans, ie emotions. This topic talks about building a model which can detect an emotion from an image. There key points to be followed are:

- Data 

The dataset taken was https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset


- Model building

The model architecture consists of CNN Layer, Max Pooling, Flatten and Dropout Layers.

- Training

The model was trained by using variants of above layers mentioned in model building and by varying hyperparameters. The best model was able to achieve 75.1% of validation accuracy.

- Testing

The model was tested with sample images.

The model will be able to detect 7 types of emotions:
- Angry:

![angry](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/12ec5aec-aa3f-430d-bc69-9f7ed6425413)

- Sad : 
 
![sad](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/35980614-cba7-4367-a338-a6bf59fcbf3c)


- Surprise:

![surprise](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/d52130a7-8333-4e28-9554-e53f470d6c7b)

- Happy:

![happy](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/2dcb8110-fc5e-4df2-9019-c7dc16389a63)

- Neutral :
 
![naturel](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/d8765534-9790-46d7-91ba-95daed8c3656)


- Fear:


![fear](https://github.com/Bouchnak-Maher/Emotion_Detection-CNN/assets/94197705/8a8bdd24-bad7-4511-a388-53bb64cb9d28)
 
