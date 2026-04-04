# deep-learning-project
# Image Classification using Transfer Learning (CIFAR-10)

## 📌 Project Overview

This project implements an image classification model using transfer learning on the CIFAR-10 dataset. A pretrained ResNet18 model is fine-tuned to classify images into 10 categories such as airplane, car, bird, cat, etc.

## 🚀 Technologies Used

* Python
* PyTorch
* Torchvision
* Matplotlib

## 📊 Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

## 🔧 Methodology

* Applied data augmentation (random horizontal flip)
* Used pretrained ResNet18 model
* Modified final fully connected layer for 10 classes
* Trained model using CrossEntropyLoss and Adam optimizer

## 📈 Results

* Training Loss Curve plotted
* Model Accuracy: ~70–80% (depending on epochs)

## 💾 Model Saving

The trained model is saved using:

```
torch.save(model.state_dict(), "model.pth")
```

## 🔍 Inference

To run inference:

1. Load the saved model
2. Set model to evaluation mode
3. Pass input image to get prediction

## ▶️ How to Run

1. Install dependencies:

```
pip install torch torchvision matplotlib
```

2. Run the Jupyter Notebook
3. Execute all cells

## 📌 Output

* Trained model file (`model.pth`)
* Accuracy and loss graphs
* Sample predictions

## 📚 Conclusion

This project demonstrates how transfer learning can be used to build efficient image classifiers with limited data and training time.
