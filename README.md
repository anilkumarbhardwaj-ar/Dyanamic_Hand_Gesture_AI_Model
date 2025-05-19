# Dynamic-Hand-Gestures-Recogonition
🖐️Dynamic Hand Gesture Recognition using MediaPipe &amp; LSTM This project implements real-time dynamic hand gesture recognition using MediaPipe for hand keypoint detection and an LSTM-based deep learning model for gesture classification. It supports training on custom datasets and provides live webcam-based gesture recognition.

--Features:

1.Extracts 3D hand landmarks using MediaPipe

2.Processes gesture sequences of 37 frames

3.Trains an LSTM model on extracted keypoint sequences

4.Real-time prediction with webcam support

5.Displays FPS and prediction confidence

--Dataset:

Used 20bn-jester dataset and taken only 6 classes from it 

--Model Architecture:

1.Input: 37 frames × 63 keypoints (21 landmarks × 3)

2.LSTM: 2 layers, hidden size = 128

Steps 

ENV PORT=5000

ENV ENVIRONMENT=development

RUN pip install -r requirements.txt

INSTALL PYTHON3

