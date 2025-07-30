# 🔢 MNIST Digit Classifier with CNN

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the **MNIST** dataset. Built using TensorFlow and Keras, the model achieves over **99% accuracy** on the test set.

---

## 🧠 Model Architecture

The CNN architecture used:

- Input Layer: 28x28 grayscale images
- Conv2D (16 filters, 3x3, ReLU, same padding)
- Conv2D (32 filters, 3x3, ReLU, same padding)
- MaxPooling2D
- Conv2D (32 filters, 3x3, ReLU, valid padding)
- Flatten
- Dense (32 units, ReLU)
- Dense (16 units, ReLU)
- Output: Dense (10 units, Softmax)

---

## 📊 Performance

| Metric | Value |
|--------|-------|
| Test Accuracy | **~99.0%** |
| Precision | 0.98–1.00 |
| Recall | 0.98–1.00 |
| F1-score | 0.98–1.00 |

📝 Classification report included in the notebook.


---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn

---

## 📈 Training Visualization

- Plots training accuracy/loss and validation accuracy/loss over 10 epochs
- Confirms excellent learning behavior without overfitting

---

## 🚀 How to Run

1. **Clone the repo**:

```bash
git clone https://github.com/jim-X-AI/MNIST-Digit-Classifier-CNN.git
cd MNIST-Digit-Classifier-CNN

