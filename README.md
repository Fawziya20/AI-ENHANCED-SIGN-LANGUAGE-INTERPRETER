# AI-ENHANCED-SIGN-LANGUAGE-INTERPRETER

### Overview:FGSFGF
ssss hgjhjh
This project implements a Hand Gesture Recognition system using the MediaPdipe library in Python. The goal is to recognize hand signs and finger gestures, facilitating a sign language interpreter enhanced by artificial intelligence.
### Contentsjhjnhj
fEF 1) Sample Program (app.py):<br>dsd
The main execution program for the sign language interpreter.


 hand_sign_model.tflite: TFLite model file for hand sign recognition.<br>
 hand_sign_labels.txt: Text file containing labels for hand sign classes.<br>dssdsdwsdw
 hand_sign_model_training_data.csv: Dataset used for training the hand sign recognition model.<br>
 hand_sign_model_training.ipynb: Jupyter notebook for model training and learning.<br>

 3)Finger Gesture Recognition Model (TFLite) and Related Files:

 finger_gesture_model.tflite: TFLite model file for finger gesture recognition.<br>
 finger_gesture_labels.txt: Text file with labels for finger gesture classes.<br>
 finger_gesture_model_training_data.csv: Dataset used for training the finger gesture recognition model.<br>
 finger_gesture_model_training.ipynb: Jupyter notebook for model training and learning.<br>

### Requirements
->mediapipe 0.10.7<br>
->OpenCV 4.8.1 or Later<br>
->Tensorflow 2.14.0 or Later (tf-nightly 2.5.0.dev or later required only when creating a TFLite for an LSTM model)<br>
->scikit-learn 0.23.2 or Later (required only if you want to display the confusion matrix)<br>
->matplotlib 3.3.2 or Later (required only if you want to display the confusion matrix)<br>

### Features
->Hand Sign Recognition: Recognizes hand signs through a webcam.<br>
->Finger Gesture Recognition: Detects finger gestures in real-time.<br>
->Artificial Intelligence: Utilizes artificial intelligence for accurate gesture interpretation.<br>
->Real-time Feedback: Overlays the predicted gestures on the live video stream.<br>
->Model Training: Allows users to collect and modify training data for continuous improvement.<br>
->Dynamic Learning: Add or change training data and retrain the models for enhanced accuracy.<br>
->Flexible Demo Options: Specify various options such as camera device number, width, height, and confidence thresholds.<br>
->Interpretation Recommendations: Provides recommendations based on the recognized gestures.<br>

### How to Use:
1) Clone the repository: git clone https://github.com/Fawziya20/AI-ENHANCED-SIGN-LANGUAGE-INTERPRETER.git<br>
2) Navigate to the project directory: cd AI-ENHANCED-SIGN-LANGUAGE-INTERPRETER<br>
3) Install the required dependencies: pip install -r requirements.txt<br>
4) Run the sample program: python app.py<br>

### Architecture Diagram/Flow:
![image](https://github.com/Fawziya20/AI-ENHANCED-SIGN-LANGUAGE-INTERPRETER/assets/75235022/8cd6f8d2-66c7-4bea-bda9-567714dd83f5)


### Output:
![image](https://github.com/Fawziya20/AI-ENHANCED-SIGN-LANGUAGE-INTERPRETER/assets/75235022/107c9d21-b8f8-4850-a93f-7a21b74b269d)


### Result
The Hand Sign Recognition System is an innovative application designed for real-time recognition of hand gestures through a webcam. Employing the MediaPipe library and a carefully crafted deep learning model, the system accurately identifies and interprets diverse hand signs, enhancing communication through gesture recognition.<br>

In the context of the Hand Sign Recognition System, users can seamlessly communicate using sign language, and the system provides immediate feedback by overlaying the recognized gestures on the live video stream. This project caters to individuals who rely on sign language for communication, offering a valuable tool for inclusive and accessible interaction.<br>

This application is beneficial for diverse users, including individuals learning sign language, researchers exploring computer vision applications, and developers interested in gesture recognition and human-computer interaction. The Hand Sign Recognition System represents a significant step toward breaking communication barriers and fostering inclusive technology.<br>
