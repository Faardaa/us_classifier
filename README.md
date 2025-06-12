# ÜŞ Letter Classification with CNN

Hello! This is my deep learning project where I built a **Convolutional Neural Network (CNN)** to classify the Azerbaijani letters **"ü"** and **"ş"** from images.

---

## 📚 About the Project

This project is about recognizing two special Azerbaijani letters: **ü** and **ş**.  
The coolest part is that the **dataset is fully handmade!**

Me and my mom wrote each letter on paper, and I took pictures of them.  
So this project is not just technical — it’s also personal. ❤️

---

## 🚀 What I Did
- Collected the dataset by handwriting the letters with my mom.
- Took pictures of the handwritten letters and organized them into folders.
- Split the dataset into **training**, **validation**, and **testing** sets.
- Applied **data augmentation** to improve the model’s generalization.
- Built a CNN model using TensorFlow.
- Trained the model and visualized accuracy and loss graphs.
- Evaluated the model using:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC AUC Score
- Visualized some predictions to see how the model performs in practice.

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Scikit-Learn
- Numpy

---

## 🗂️ Dataset

The dataset is **handwritten by me and my mom** ❤️  
It is organized like this:
  📂 dataset
  ├── 📂 ü # Handwritten images of the letter ü
  └── 📂 ş # Handwritten images of the letter ş


---

## ⚙️ How to Run

1. Clone the repository.
   ```bash
   git clone https://github.com/Faardaa/us_classifier.git
   
2. Install the required libraries.
   ```bash
   pip install -r requirements.txt
   
3.Run the notebook.
  ```bash
  üş_classification.ipynb
