Introduction

Nonverbal communication signals such as facial expressions and gestures play a vital part in interpersonal relationships. This facial expression detection software analyzes human faces to recognize seven fundamental expressions: happiness, anger, sadness, fear, neutral, surprise, and disgust. The software can also detect pain and potentially identify if someone is lying.

Technology Overview
Deep learning, particularly convolutional neural networks (CNN), has significantly advanced in recent years. CNNs are highly accurate for image recognition tasks, making them suitable for commercial applications. In this project, we utilize CNNs to build a facial expression recognition system.

Dataset
We use the FER2013 dataset, which contains 35,887 grayscale face images of size 48 x 48, sourced from Kaggle. This dataset is widely used for facial expression recognition research.

Methodology

Model Training:

Data Preparation: The dataset is split into 80% for training and 20% for testing.
CNN Architecture: A deep learning model is designed using CNN to extract features from the images.
Training: The model is trained on the training dataset to learn the various facial expressions.
Dynamic Input Implementation:

Webcam Integration: A camera window is opened from the device to capture real-time video.
Frame Processing: Video frames are extracted and processed using the trained CNN model.
Prediction: The model predicts the emotion displayed in each frame.
Results and Storage:

The predicted emotions are stored in a file for further analysis and testing.
Conclusion

The software successfully recognized emotions in the FER2013 dataset images. We extended our model to handle dynamic input by integrating webcam video feed. The system predicted emotions in real-time, demonstrating its utility in various applications.
