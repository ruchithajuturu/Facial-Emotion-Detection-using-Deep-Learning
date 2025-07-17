# Emotion detection using deep learning

# 😃 Facial Emotion Detection using Deep Learning

A deep learning project that classifies facial expressions into **seven emotions** using a Convolutional Neural Network trained on the FER-2013 dataset. This implementation uses OpenCV for real-time emotion detection from webcam feed.

---

## 📌 Emotion Categories
- Angry 😠
- Disgusted 🤢
- Fearful 😨
- Happy 😄
- Neutral 😐
- Sad 😢
- Surprised 😲

---

## 🧠 Dataset

The model is trained on the **FER-2013** dataset published in the International Conference on Machine Learning (ICML). It includes 35,887 grayscale 48x48 face images labeled with seven emotions.

[🔗 Kaggle Dataset – FER2013](https://www.kaggle.com/datasets/deadskull7/fer2013)

---

## 📦 Dependencies

- Python 3.x
- [OpenCV](https://opencv.org/)
- [TensorFlow 2.x](https://www.tensorflow.org/)
- Keras API via `tensorflow.keras`

Install required packages:

```bash
pip install -r requirements.txt

**🔧 Project Structure

├── src/
│   ├── data/                         # FER2013 data
│   ├── model.h5                      # Pre-trained model
│   ├── emotions.py                   # Main script
│   ├── dataset_prepare.py           # Optional CSV-to-image converter
│   └── haarcascade_frontalface_default.xml
├── imgs/
│   └── accuracy.png
├── requirements.txt
└── README.md

**🚀 How to Use
git clone https://github.com/ruchithajuturu/Facial-Emotion-Detection-using-Deep-Learning.git
cd Facial-Emotion-Detection-using-Deep-Learning

**Option 1: Train Your Own Model
cd src
python emotions.py --mode train

**Option 2: Use Pre-trained Model
cd src
python emotions.py --mode display

**📈 Performance
 CNN Model: 4 convolutional layers
 Test Accuracy: 63.2% (after 50 epochs)
 Real-time detection supported via webcam

🔍 Algorithm Steps
 Face detection using Haar Cascade
 Extract face region and resize to 48x48
 Feed image to CNN
 Apply softmax to predict emotion
 Display emotion label on webcam frame

🧑‍💻 Author
Ruchitha Juturu
📍 Passionate about Data Engineering, Deep Learning, AI Projects, and Women Empowerment Tools
🔗 GitHub | LinkedIn | 
