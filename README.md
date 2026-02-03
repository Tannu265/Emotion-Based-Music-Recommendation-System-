# Emotion Based Music Recommendation System

# 🎵 RhythmiQ –Music Recommendation System

## 📌 Overview

RhythmiQ is an emotion-based music recommendation system that uses facial expression recognition to detect a user’s emotional state in real time and automatically play music that matches their mood. By combining Computer Vision and Deep Learning, the system delivers a personalized and emotionally intelligent music experience without requiring any manual input from the user.
The system captures live video through a webcam, detects the user’s face using OpenCV, predicts emotions using a trained Convolutional Neural Network (CNN), and recommends music accordingly. This project demonstrates how AI can understand human emotions and enhance digital experiences through smart automation.

---
## 🎯 Features

- Real-time facial emotion detection
- CNN-based emotion classification
- Automatic music recommendation
- Webcam-based interaction
- Emotion-aware personalized playlists

  
---

## 😊 Emotions & Music Recommendation
- Happy 😄 – Upbeat and energetic tracks (Pop, Dance)
- Sad 😢 – Calm, slow-tempo songs (Lo-fi, Acoustic)
- Angry 😠 – Intense or expressive music (Rock, Metal)
- Surprised 😲 – Dynamic or cinematic tracks
- Neutral 😐 – Balanced or favorite playlists
- Fear 😨 – Soothing and relaxing music
- Disgust 🤢 – Neutral music or track skip

  
---

## 🛠️ Technologies Used
- Python
- OpenCV – Face detection & image processing
- TensorFlow & Keras – Deep learning & CNN model
- Scikit-learn – Machine learning utilities
- NumPy & Pandas – Data handling
- Matplotlib – Data visualization
- Flask
- HTML/CSS

  
---
## Emotion-Based-Music-Recommendation-System/
- │
- ├── app.py                      # Main Flask application
- ├── emotion.py                  # Emotion detection logic
- ├── facialemotionmodel.h5       # Trained CNN model for emotion recognition
- ├── requirements.txt            # Python dependencies
- ├── Procfile                    # Deployment configuration
- ├── setup.sh                    # Setup script for deployment
- ├── LICENSE                     # License file
- │
- ├── data/
- │   ├── filtered_track_df.csv   # Music dataset
- │   └── preprocess_data.ipynb   # Dataset preprocessing notebook
- │
- └── README.md

---

## ⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/Tannu265/Emotion-Based-Music-Recommendation-System.git
cd Emotion-Based-Music-Recommendation-System

2️⃣ Create a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Application
python app.py

---

## 📸 How It Works
- The webcam captures the user’s face.
- A CNN model predicts the user’s emotion.
- The system filters songs related to that emotion.
- Music recommendations are displayed instantly.

---

# 📊 Dataset
- The music dataset (filtered_track_df.csv) contains tracks tagged with emotional attributes.
- Data preprocessing steps are documented in preprocess_data.ipynb.

---

## 📌 Conclusion
RhythmiQ successfully integrates facial emotion recognition with automated music recommendation, creating a smart and emotionally responsive system. By leveraging AI, deep learning, and computer vision, the project demonstrates how technology can adapt to human emotions and provide a more personalized, empathetic, and engaging user experience.

---
## Author 
**Tannu Jha**
