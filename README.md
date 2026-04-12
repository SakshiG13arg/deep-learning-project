# deep-learning-project
# Image Classification using Transfer Learning (ResNet18 on CIFAR-10)

## 📌 Overview

This project implements an image classification system using **Transfer Learning** with a pretrained ResNet18 model. The model is trained and evaluated on the CIFAR-10 dataset, which contains 10 different image classes.

---

## 🎯 Objectives

* Apply transfer learning using ResNet18
* Train a deep learning model on image data
* Evaluate model performance using metrics and visualizations
* Build an image prediction system

---

## 📂 Dataset

* **Dataset Used:** CIFAR-10
* **Classes:**

  * Airplane
  * Automobile
  * Bird
  * Cat
  * Deer
  * Dog
  * Frog
  * Horse
  * Ship
  * Truck

The dataset is automatically downloaded using torchvision.

---

## ⚙️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🧠 Model Details

* Pretrained **ResNet18** model used
* Final fully connected layer modified for 10 classes
* Optimizer: Adam
* Loss Function: CrossEntropyLoss

---

## 🚀 Features

* Transfer learning using ResNet18
* Training and evaluation pipeline
* Training loss and accuracy visualization
* Confusion matrix for performance evaluation
* Image prediction system
* Visualization of predicted vs actual labels

---

## 📊 Visualizations

The project includes:

* Training Loss Curve
* Training Accuracy Curve
* Confusion Matrix Heatmap
* Sample Image Predictions

---

## 🧪 How to Run

1. Clone the repository or download files
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook
4. Run all cells

---

## 📈 Results

* Model successfully learns image features from CIFAR-10
* Achieves good classification performance
* Predictions visually verified using sample images

---

## 🔮 Future Improvements

* Increase number of training epochs
* Add data augmentation
* Use more advanced architectures (ResNet50, EfficientNet)
* Deploy as a web application

---

## 📎 Project Structure

```
Task-2/
│
├── Image_Classification.ipynb
├── README.md
├── requirements.txt
```

---

## 👨‍💻 Author

Sakshi Garg
