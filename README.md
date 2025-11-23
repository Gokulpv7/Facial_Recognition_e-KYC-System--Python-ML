👁️ Facial Recognition & e-KYC System (CNN + OpenCV + OCR + Voice Input)

This repository contains an end-to-end AI-powered identity verification system that integrates facial recognition, OCR-based Aadhaar scanning, speech-to-text input, and CNN-based custom face training. The project demonstrates real-time authentication and can be used for e-KYC, attendance systems, or secure access systems.

🚀 Features

🧠 Custom Face Recognition using CNN

🎤 Voice-based input using Speech Recognition

📷 Live Webcam Capture

🧾 OCR Text Extraction from Aadhaar (Image/PDF)

👤 Face Matching with DeepFace

🌐 Flask API for e-KYC Workflow

📊 Dataset creation and real-time prediction

🛠 Designed for real-world applications like:

Banking e-KYC

Automated Attendance Systems

Identity Verification

📁 Project Structure
File	Description
voice.py	Handles voice-based input using speech recognition. 

voice


ekyc.py	Full e-KYC workflow (OCR + face match + Flask API). 

ekyc


Facial Recognition using CNN Algorithm.txt	Model training and real-time prediction script. 

Facial Recognition using CNN Al…

🧠 Technologies Used
Category	Tools
Language	Python
Computer Vision	OpenCV, DeepFace, Haarcascade
Deep Learning	TensorFlow / Keras CNN
Voice Recognition	SpeechRecognition + Google API
OCR	Tesseract + pdf2image
Backend	Flask
Testing/Deployment	Webcam, Local Runtime
🔧 Setup & Installation
pip install opencv-python deepface flask pdf2image tensorflow pytesseract SpeechRecognition


Install Tesseract OCR from:
➡ Windows: https://github.com/tesseract-ocr/tesseract

Update path in ekyc.py if needed.

🧪 How to Use

Create a dataset using webcam
→ Run the CNN dataset script

Train the model
→ Automatically saves face_recognition_model.keras

Run e-KYC API
→ Upload Aadhaar + verify live face

Optionally use voice recognition to interact

📌 Example Output

✔ Face Verified — e-KYC Approved

❌ Face Not Matched — Verification Failed

🔒 Future Improvements

Cloud deployment

Liveness verification (anti-spoofing)

Mobile app integration

🧾 License

MIT License — Free for academic and research use.

🤝 Contributions

Pull requests and improvements are welcome!
