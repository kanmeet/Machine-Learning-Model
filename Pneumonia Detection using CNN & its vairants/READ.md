
# 🩺 Pneumonia Detection using CNN & Its Variants

This project uses Convolutional Neural Networks (CNNs) and its variants to detect pneumonia from chest X-ray images. The objective is to assist radiologists and healthcare professionals in early and accurate diagnosis of pneumonia using deep learning techniques.

---

## 📁 Project Structure

pneumonia_detection/
│
├── Capstone_Project_Milestone2.ipynb # Main notebook
├── pneumonia_dataset/ # X-ray images (train/test/val)
├── model/ # Saved models (optional)
├── requirements.txt # Required Python libraries
└── README.md # Project overview


## 🧠 Problem Statement

Pneumonia is a potentially fatal lung infection. Traditional diagnosis from chest X-rays is time-consuming and requires trained professionals. This project aims to automate the detection of pneumonia using a trained deep learning model on labeled X-ray images.

---

## 📦 Dataset

- **Source**: [Kaggle Chest X-Ray Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- **Structure**:
  - `train/`: Normal and pneumonia cases
  - `test/`: Evaluation images
  - `val/`: Validation data

---

## ⚙️ Technologies Used

- Python 🐍
- TensorFlow / Keras
- NumPy / Pandas
- Matplotlib / Seaborn
- OpenCV (optional for preprocessing)

---

## 🏗️ Model Architecture

- Custom CNN
- Pretrained models (optional): VGG16, ResNet50, etc.
- Layers:
  - Convolutional + MaxPooling
  - Dropout
  - Dense
  - Softmax/Sigmoid Output


## 🎯 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📈 Results

| Model | Accuracy|
|-------|----------
| CNN   | 68%     |


## 💡 Key Insights

- CNN models can effectively classify chest X-ray images.
- Data augmentation helps reduce overfitting.
- Training with a balanced dataset improves generalization.


## 📝 How to Run

1. Clone the repo:
   git clone https://github.com/kanmeet/Machine-Learning-Model.git
   cd pneumonia_detection/

Install dependencies:
pip install -r requirements.txt

Run the notebook:
jupyter notebook Capstone_Project_Milestone2.ipynb

📌 Recommendations

Fine-tune using transfer learning (e.g., ResNet, EfficientNet)

Deploy as a web app for hospitals (e.g., Streamlit)

Integrate with mobile apps for real-time diagnosis


👩‍⚕️ Author

Anmeet Kaur
📧 Email | 🔗 GitHub
