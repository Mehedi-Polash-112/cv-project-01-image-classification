# CV Project 01 — Cat vs Dog Image Classification (ResNet18)

## 📌 Project Overview

This project demonstrates a complete deep learning workflow for image classification using **Transfer Learning**.

A pretrained **ResNet18** model was fine-tuned to classify images into two categories:

- 🐱 Cat  
- 🐶 Dog  

The project was implemented using **PyTorch** and trained in **Google Colab**.

---

## 🎯 Objective

The goals of this project were:

- Understand the full Computer Vision pipeline
- Apply transfer learning with a pretrained CNN
- Train and evaluate a binary image classifier
- Generate performance metrics (accuracy, confusion matrix, classification report)
- Perform prediction on new images

---

## 🧠 Model Details

- Architecture: ResNet18 (Pretrained on ImageNet)
- Framework: PyTorch
- Input Size: 224 × 224
- Loss Function: CrossEntropyLoss
- Optimizer: Adam (learning rate = 1e-4)
- Training Platform: Google Colab (CPU/GPU)

---

## 📊 Evaluation Metrics

The model was evaluated using:

- Validation Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

Evaluation outputs are available in the `results/` folder:

- `confusion_matrix.png`
- `classification_report.txt`

---

## 🖼️ Inference on New Images

The notebook allows:

- Uploading custom images
- Running prediction
- Displaying predicted class
- Showing class probabilities

---

## 📂 Project Files

- `cv_project_01.ipynb` — Training and evaluation notebook  
- `resnet18_cats_dogs.pth` — Trained model weights  
- `results/confusion_matrix.png` — Confusion matrix visualization  
- `results/classification_report.txt` — Detailed classification metrics  
- `README.md` — Project documentation  

---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. Upload your own images for prediction  
4. View evaluation results in the `results/` folder  

---

## 🛠️ Technologies Used

- Python  
- PyTorch  
- Torchvision  
- scikit-learn  
- Google Colab  

---

## 👨‍🎓 Author

**Mehedi Mohammad**  
MS Veterinary Medical Science (AI Research Focus)  
Electrical & Electronic Engineering Background  
Special Interest: AI in Veterinary and Biomedical Applications
