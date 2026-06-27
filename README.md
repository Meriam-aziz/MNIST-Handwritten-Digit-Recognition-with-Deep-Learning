# ✍️ Handwritten Digit Recognition System using Deep Learning

## 📌 Overview

This project presents a Deep Learning model that recognizes handwritten digits (0–9) using the MNIST dataset. The model classifies grayscale images of handwritten digits and predicts the corresponding digit with high accuracy.

---

## 🎯 Objective

The main objective of this project is to build an accurate image classification model capable of recognizing handwritten digits from the MNIST dataset using Deep Learning techniques.

---

## 📊 Dataset

The project uses the **MNIST** dataset, which contains:

* **70,000** handwritten digit images
* **28 × 28** grayscale images
* **10 classes** representing digits **0–9**
* Training set: **60,000** images
* Test set: **10,000** images

---

## ⚙️ Workflow

1. Load the MNIST dataset
2. Data preprocessing (normalization and reshaping)
3. Build the Deep Learning model
4. Train the model
5. Evaluate the model
6. Predict handwritten digits

---

## 🤖 Model Used

* Convolutional Neural Network (CNN)

---

## 📈 Evaluation Metrics

* Accuracy
* Loss
* Confusion Matrix

---

## 🖼️ Results

### Final Prediction Result

![Final Result](images/final_result.png)

The trained CNN model successfully recognizes handwritten digits from the MNIST dataset with high accuracy.

---

## 🚀 Key Insights

* CNN significantly outperforms traditional Machine Learning algorithms for image classification tasks.
* Image normalization improves model performance and training stability.
* The trained model achieves excellent accuracy on unseen handwritten digit images.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Matplotlib
* TensorFlow
* Keras
* Jupyter Notebook

---

## ▶️ How to Run

```bash
git clone https://github.com/your-username/MNIST-Handwritten-Digit-Recognition-with-Deep-Learning.git

cd MNIST-Handwritten-Digit-Recognition-with-Deep-Learning

pip install -r requirements.txt

jupyter notebook AI.ipynb
```

---

## 📁 Project Structure

```text
MNIST-Handwritten-Digit-Recognition-with-Deep-Learning/
│
├── images/
│   └── final_result.png
├── AI.ipynb
├── README.md
└── requirements.txt
```

---

## 👩‍💻 Author

**Meriam Aziz**

---

## ⭐ Future Improvements

* Develop a real-time handwritten digit recognition web application using Streamlit.
* Deploy the trained model for online inference.
* Improve the CNN architecture for even higher accuracy.
* Extend the project to recognize handwritten letters and characters.

