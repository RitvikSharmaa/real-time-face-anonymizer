# 🕶️ Real-Time Face Anonymizer (OpenCV)

A real-time **face detection and anonymization system** built using **Python and OpenCV**, designed to protect user privacy by detecting faces from a live webcam feed and anonymizing them in real time.

This project demonstrates practical computer vision techniques using **Haar Cascade classifiers**, real-time video processing, and image manipulation.

---

## ✨ Features

* 📷 Real-time webcam capture
* 🙂 Face detection using **Haar Cascade Classifier**
* 🔁 **Mirrored camera view** (selfie-style)
* 🟩 Face localization using bounding boxes
* 🕶️ Face anonymization using **Gaussian Blur**
* ⚡ Runs smoothly in real time
* 🧹 Simple, clean, beginner-friendly implementation

---

## 🧠 How It Works (High-Level Overview)

1. Capture live video frames from the webcam
2. Mirror the frame horizontally for a natural view
3. Convert each frame to grayscale
4. Detect faces using a pre-trained Haar Cascade model
5. Extract face regions (ROIs)
6. Apply anonymization (blur) to detected faces
7. Display the processed video in real time

---

## 🔍 Why Haar Cascade?

Haar Cascades are a classical computer vision technique that:

* Are lightweight and fast
* Require no GPU
* Work well for frontal face detection
* Are ideal for real-time and educational applications

This makes them a great choice for learning and rapid prototyping.

---

## 🗂️ Project Structure

```
real-time-face-anonymizer/
│
├── main.py              # Face detection & anonymization logic
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV**
* **Haar Cascade Classifier**

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/RitvikSharmaa/real-time-face-anonymizer.git
cd real-time-face-anonymizer
```

### 2️⃣ (Optional) Create a virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is not present:

```bash
pip install opencv-python
```

---

## ▶️ Usage

Run the application:

```bash
python main.py
```

* Press **`q`** to quit the application.

---

## 🎛️ Configuration & Tuning

You can fine-tune face detection accuracy by adjusting:

```python
scaleFactor=1.2
minNeighbors=5
minSize=(60, 60)
```

* Lower `scaleFactor` → higher accuracy, slower speed
* Higher `minNeighbors` → fewer false positives

---

## 📌 Use Cases

* Privacy-preserving video applications
* Real-time face censoring
* Educational computer vision projects
* Surveillance and monitoring prototypes
* Interview and portfolio demonstrations

---

## 🧠 Learning Outcomes

By working on this project, you gain hands-on experience with:

* Real-time video processing
* Face detection techniques
* Haar Cascade classifiers
* Image preprocessing (grayscale conversion)
* Region of Interest (ROI) operations
* Privacy-aware computer vision design

---

## 🚀 Future Improvements

* 🎭 Pixelation-based anonymization
* 👀 Eye-only anonymization
* 🎥 Support for video file anonymization
* 📊 FPS counter and performance metrics
* 🧠 Upgrade to deep learning–based detectors

---

## 📄 License

This project is open-source and intended for learning, experimentation, and demonstration purposes.

---
