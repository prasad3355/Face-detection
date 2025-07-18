# Face Detection & Recognition using OpenCV and Keras

A real-time face detection and recognition system using OpenCV, IP Webcam, and a trained CNN model.

## 🚀 Features
- Real-time face detection (Haar Cascade)
- Face data collection from Android IP Webcam
- Grayscale preprocessing and resizing
- CNN-based face recognition (Keras)

## 🗂 Project Structure
```
Face-detection/
├── images/                # Collected face images
├── clean data/           # Processed image & label files
├── collect_data.py       # Capture faces from webcam
├── consolidated_data.py  # Preprocess and save data
├── recognize.py          # Real-time face recognition
├── final_model.h5        # Trained CNN model
├── haarcascade_frontalface_default.xml
└── README.md
```

## ⚙️ Setup
```bash
pip install opencv-python numpy keras matplotlib
```

## 📷 IP Webcam Setup
- Install **IP Webcam** app from Play Store
- Start server and use the image URL (e.g., `http://192.168.x.x:8080/shot.jpg`)
- Replace the URL in your Python scripts

## 🧪 How to Use
```bash
python collect_data.py         # Step 1: Capture 100 face images
python consolidated_data.py    # Step 2: Preprocess and save .p files
python recognize.py            # Step 3: Real-time recognition
```

## 🧠 Model Info
- Input: 100x100 grayscale images
- Labels: ['Ajit', 'Alok', 'Prasad', 'Suman']
- Model format: `.h5` (Keras CNN)

## 👤 Author
**Prasad Swain**

## 📝 License
This project is for educational and personal use only.
