🤟 Gesture2Talk (VisionVoice)

Real-Time Sign Language Translator

Gesture2Talk is a real-time web-based application that bridges the communication gap between deaf or speech-impaired individuals and the general public. It converts hand gestures (sign language) into readable text and audible speech using computer vision and machine learning.

---

🚀 Features

- 🎥 Live webcam-based gesture detection
- ✋ Hand landmark tracking using computer vision
- 🔤 Real-time gesture-to-text conversion
- 🔊 Text-to-speech output
- 📊 Confidence score display
- 💬 Sentence formation & conversation history
- 💡 Word suggestions for faster communication
- 🎨 Modern dark-themed UI with smooth animations
- 📱 Responsive design for mobile and desktop

---

🧠 How It Works

1. The system captures live video from the user's webcam
2. Hand landmarks (21 key points) are detected using computer vision
3. Extracted features are passed to a trained ML model
4. The model predicts the corresponding alphabet
5. Letters combine to form words and sentences
6. Output is displayed on screen and can be spoken aloud

---

🛠️ Tech Stack

Frontend

- HTML
- CSS
- JavaScript

Backend

- Python
- Flask

AI / ML

- OpenCV
- MediaPipe
- NumPy
- TensorFlow / Keras

---

📂 Project Structure

Gesture2Talk/
│
├── frontend/
│   └── index.html
│
├── backend/
│   ├── app.py
│   ├── model.h5
│   └── utils/
│
├── dataset/
├── requirements.txt
└── README.md

---

⚙️ Setup & Installation

1. Clone the repository

git clone https://github.com/your-username/Gesture2Talk.git
cd Gesture2Talk

2. Install dependencies

pip install -r requirements.txt

3. Run the backend server

python app.py

4. Open frontend

- Open "index.html" in your browser
- Allow camera access

---

🔗 API Endpoints

Endpoint| Method| Description
"/predict"| POST| Get gesture prediction
"/speak"| GET| Convert text to speech
"/sentence/backspace"| GET| Remove last letter
"/sentence/clear"| GET| Clear sentence
"/history"| GET| Fetch conversation history

---

🎯 Use Cases

- Education (classroom communication)
- Healthcare (doctor-patient interaction)
- Public services
- Daily conversations

---

⚠️ Limitations

- Sensitive to lighting conditions
- May struggle with fast or complex gestures
- Accuracy depends on trained dataset
- Requires visible hand in camera frame

---

💡 Future Improvements

- Multi-hand detection
- Full word recognition instead of letters
- AI-based smart suggestions
- Mobile app version
- Offline mode support

---

👥 Team

- Sajal Agarwal (Team Lead)
- Shruti Tiwari
- Shubhi Bunkar
- Disha Gautam

---

🏆 Hackathon Project

Built for innovation, accessibility, and real-world impact — Gesture2Talk aims to make communication inclusive for everyone.

---

❤️ Acknowledgements

- MediaPipe
- OpenCV
- TensorFlow
- Open Source Community

---

📌 License

This project is open-source and available under the MIT License.

---
