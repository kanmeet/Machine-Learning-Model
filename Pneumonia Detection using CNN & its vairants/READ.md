# Pneumonia Detection using CNN & Its Variants

This project involves building deep learning models to automatically detect **pneumonia** from chest X-ray images using **Convolutional Neural Networks (CNN)** and its advanced variants. The goal is to assist radiologists and healthcare professionals in identifying pneumonia cases quickly and accurately.

---

## 📁 Project Structure


---

## 📊 Dataset

- **Source**: [Kaggle - Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Categories**:
  - Normal
  - Pneumonia (bacterial/viral)

---

## 🧠 Models Used

1. **Basic CNN**
   - 3 Conv layers + MaxPooling
   - Dense layer + Sigmoid output

2. **CNN with Data Augmentation**
   - Added `ImageDataGenerator` for better generalization

3. **CNN with Dropout Regularization**
   - Prevents overfitting with `Dropout(0.5)`

4. **Transfer Learning with VGG16**
   - Pretrained VGG16 + custom classifier layers

---

## 📈 Evaluation Metrics

- Accuracy
- Precision / Recall
- F1-Score
- Confusion Matrix
- ROC Curve (AUC)

---

## 🧪 Sample Results

| Model                     | Accuracy | Recall | Precision | F1-Score |
|--------------------------|----------|--------|-----------|----------|
| Basic CNN                | 85%      | 84%    | 86%       | 85%      |
| CNN + Augmentation       | 88%      | 87%    | 89%       | 88%      |
| CNN + Dropout            | 89%      | 88%    | 90%       | 89%      |
| VGG16 Transfer Learning  | **93%**  | 92%    | 94%       | 93%      |

---

## 🛠️ Requirements

```bash
tensorflow
keras
matplotlib
seaborn
scikit-learn
opencv-python

