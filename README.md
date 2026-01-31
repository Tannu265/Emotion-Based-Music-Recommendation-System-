# Emotion-Based-Music-Recommendation-System-
---
# 🎵 FaceBeats – Emotion-Based Music Recommendation System
---
# 📌 Overview

FaceBeats is an intelligent emotion-based music recommendation system that uses facial expression recognition to detect a user’s current emotional state and automatically play music that matches their mood.
By combining Computer Vision and Deep Learning, the system creates a personalized and emotionally intuitive music experience in real time.

Instead of manually choosing songs, users simply sit in front of a webcam, and FaceBeats takes care of the rest 🎧✨
---

# 🎯 Key Features

Real-time facial emotion detection using a webcam
Emotion classification using a Convolutional Neural Network (CNN)
Automatic music recommendation based on detected emotion
Smooth integration of OpenCV and TensorFlow/Keras
Supports multiple human emotions
---

# 😊 Emotions Recognized & Music Behavior
Emotion	Facial Expression	Music Recommendation
Happy 😄	Smile, relaxed eyes	Upbeat & energetic tracks (Pop, Dance)
Sad 😢	Droopy eyes, downturned mouth	Soft, slow-tempo songs (Lo-fi, Acoustic)
Angry 😠	Furrowed brows, clenched jaw	Intense or expressive music (Rock, Metal)
Surprised 😲	Raised eyebrows, open mouth	Dynamic or cinematic tracks
Neutral 😐	No strong expression	Balanced or favorite playlists
Fear 😨	Wide eyes, tense face	Calm & soothing music
Disgust 🤢	Wrinkled nose, curled lips	Neutral music or skip track
---
# 🛠️ Tech Stack

Programming Language: Python
Computer Vision: OpenCV
Deep Learning: TensorFlow, Keras
Machine Learning: Scikit-learn
Data Handling: NumPy, Pandas
Visualization: Matplotlib
---

# 📂 Project Structure
FaceBeats/
│
├── final_model.py              # Main application (webcam + music playback)
├── emotion.py                  # Emotion prediction logic
├── cnn.py                      # CNN model architecture
├── train_CNN.py                # Training script for CNN
├── load_and_process.py         # Dataset loading & preprocessing
├── Machine_learning_models.ipynb # Model experiments & evaluation
├── haarcascade_frontalface_default.xml # Face detection model
├── Classifier.hdf5             # Trained emotion recognition model
└── README.md                   # Project documentation

# 🔄 Working Flow

Webcam Capture
Captures real-time video feed using OpenCV
Face Detection
Detects faces using Haar Cascade Classifier
Preprocessing
Converts image to grayscale
Resizes to 48×48
Normalizes pixel values
Emotion Prediction
CNN model predicts the emotion from facial features
Music Recommendation
Corresponding playlist/song is played automatically
---

# 📚 Libraries Used

cv2 (OpenCV) – Face detection & video processing
tensorflow.keras – Model building & prediction
numpy – Numerical computations
imutils – Simplified OpenCV operations
argparse – Command-line argument handling
os – File & directory operations
webbrowser – Opens music links
time – Delay handling
scikit-learn – Model evaluation & preprocessing
matplotlib – Data visualization
pandas – Dataset handling
---

# ✅ Conclusion

FaceBeats successfully demonstrates how Artificial Intelligence, Machine Learning, and Computer Vision can work together to understand human emotions and respond in a meaningful way.
By detecting emotions in real time and recommending mood-matching music, FaceBeats enhances user experience and showcases the potential of emotionally intelligent systems. This project highlights how technology can become more personal, empathetic, and engaging through AI.

---
## Author 
Tannu Jha
