# 👤 Real-Time Face Recognition System

A Python-based face recognition system using deep learning. It creates face embeddings from labeled images and performs real-time face recognition via webcam.

---

## 🚀 Features

- Face detection using Haar Cascade (OpenCV)
- Embedding generation using a pre-trained FaceNet model
- Real-time recognition using webcam
- Supports attendance/access logging
- Easily extendable with more identities

---

## 📁 Project Files

- `model.ipynb`: Generates and saves face embeddings from `images/` folder.
- `face_rec_model.ipynb`: Recognizes faces in real time using webcam and saved embeddings.

---

## ⚙️ Workflow

1. **Prepare Dataset**  
   Store images in folders: `images/Name_RollNo/`

2. **Generate Embeddings**  
   Run `model.ipynb` to extract embeddings.

3. **Real-Time Recognition**  
   Run `face_rec_model.ipynb` to start webcam-based recognition.

---

## 🛠️ Tech Stack

- Python, OpenCV
- FaceNet, scikit-learn
- Jupyter Notebook

---

## 📦 Installation

```bash
pip install opencv-python numpy scikit-learn tensorflow
