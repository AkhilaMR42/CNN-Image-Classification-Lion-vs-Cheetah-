# 🧠 CNN Image Classification – Lion vs Cheetah

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** to classify images of **lions** and **cheetahs**.
The trained model is deployed using **Streamlit**, allowing users to upload an image and get instant predictions.

---

## 🎯 Objectives

* Build a CNN model for image classification
* Train the model using a labeled dataset
* Save the trained model as `.h5`
* Deploy the model using Streamlit
* Provide a simple UI for user interaction

---

## 📂 Dataset

* The dataset contains two classes:

  * 🐆 Cheetah
  * 🦁 Lion
* Images are organized in folder format:

```
datasets/
   ├── cheetah/
   └── lion/
```

---

## 🧠 CNN Architecture

The model consists of the following layers:

* Convolution Layer (feature extraction)
* ReLU Activation
* MaxPooling Layer (dimensionality reduction)
* Flatten Layer
* Dense (Fully Connected) Layers
* Softmax Output Layer

---

## ⚙️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Streamlit

---

## 🚀 How to Run the Project

### 1️⃣ Install dependencies

```
pip install tensorflow streamlit numpy pillow
```

### 2️⃣ Train the model

Run the notebook:

```
cnn_model.ipynb
```

### 3️⃣ Run Streamlit app

```
streamlit run app.py
```

---

## 📸 Output

Upload an image through the Streamlit interface and the model predicts whether it is a **lion** or **cheetah**.

(Add screenshot here)

---

## 📁 Project Structure

```
Cnn_projects/
│
├── datasets/
│   ├── cheetah/
│   └── lion/
│
├── cnn_model.ipynb
├── cnn_model.h5
├── app.py
├── README.md
└── screenshot.png
```

---

## ✅ Results

* Model successfully classifies images into two categories
* Streamlit app provides real-time predictions

---

## 🔗 Submission

GitHub Repository Link:
(Add your GitHub link here)

---

## 📌 Conclusion

This project demonstrates how CNNs can be effectively used for image classification and deployed using Streamlit for real-world applications.
