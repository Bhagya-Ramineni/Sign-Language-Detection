# Sign-Language-Detection
A sign language recognition system using computer vision techniques to support communication for individuals who are deaf or have speech impairments.
# Sign Language Detection using CNN & MobileNet

This project implements a **sign language recognition system** using computer vision to assist individuals who are deaf or have speech impairments. It supports both **image-based classification** and **real-time gesture recognition** through webcam input.

---

##  Dataset

- Source: [Kaggle – American Sign Language Dataset](https://www.kaggle.com/datasets/ayuraj/american-sign-language-dataset)
- Trained only on **alphabet gestures (A–Z)**.

---

##  Model Training

- Model building and training are done in the file: `1.ipynb`
- Two models were trained:
  - Custom **Convolutional Neural Network (CNN)**
  - Transfer learning model using **MobileNet**
- Trained models are saved in the `Model/` directory as:
  - `CNNModel.h5`
  - `Mobilenetmodel.h5`

---

##  Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- Flask (for backend)
- HTML / CSS / JavaScript (for frontend)

---

##  How to Run

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt
2. Start the Flask server
   python app.py
3. Open your browser and go to:
http://localhost:5000

