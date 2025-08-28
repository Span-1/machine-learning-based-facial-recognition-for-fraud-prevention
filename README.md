Real-Time Face Recognition with Anti-Spoofing

A fraud prevention system that uses computer vision and deep learning to detect and verify human faces in real-time. The system prevents spoofing attempts (e.g., photos, videos, masks) by validating live presence through blink/head movement detection.

✨ Features

Real-time webcam-based face recognition

Human detection using YOLO (Ultralytics)

Automatic dataset generation for training

Face recognition using a CNN (Keras + TensorFlow)

Liveness detection to prevent spoofing

Speech-to-text & text-to-speech integration

Local logging of authentication events

🛠 Tech Stack
Tool/Library	Usage
OpenCV	Webcam access, image preprocessing
YOLO (Ultralytics)	Human detection
TensorFlow/Keras	CNN model training & testing
NumPy	Matrix operations
scikit-learn	Encoding, train-test split
pyttsx3	Text-to-speech output
🚀 How It Works

Camera Activation → Starts webcam and checks human presence

Face Detection → YOLO confirms face in frame

Dataset Creation → Captures and stores multiple images

Model Training → CNN model learns from dataset

Liveness Detection → Validates blink/head move

Face Verification → Matches with trained model

Feedback → Text-to-speech response

Logging → Saves results & timestamps

📂 Project Structure
dataset/         → Captured face images  
model/           → Saved CNN model  
logs/            → Verification logs  
main.py          → Main application  
train_model.py   → CNN training script  
requirements.txt → Dependencies  
README.md        → Documentation  

🔮 Future Scope

Deepfake detection add-on

Mobile app deployment

Cloud dashboard integration

Multi-factor biometric authentication
