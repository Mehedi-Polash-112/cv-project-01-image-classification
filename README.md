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
- Apply transfer learning using a pretrained CNN
- Train and evaluate a binary image classifier
- Generate evaluation metrics (accuracy, confusion matrix, classification report)
- Perform inference on new images

---

## 🧠 Model Details

- Architecture: ResNet18 (Pretrained on ImageNet)
- Framework: PyTorch
- Input Size: 224 × 224
- Loss Function: CrossEntropyLoss
- Optimizer: Adam (learning rate = 1e-4)
- Training Environment: Google Colab (CPU / GPU compatible)

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

The notebook includes functionality to:

- Upload custom images
- Run prediction
- Display predicted class
- Show class probabilities

---

## 📂 Project Files

- `cv_project_01.ipynb` — Training and evaluation notebook  
- `results/confusion_matrix.png` — Confusion matrix visualization  
- `results/classification_report.txt` — Detailed classification metrics  
- `README.md` — Project documentation  

> Note: Trained model weights are not uploaded due to GitHub file size limits.  
> The notebook allows full model training and reproduction of results.

---

## 🚀 How to Run

1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. The dataset downloads automatically  
4. View evaluation results in the `results/` folder  
5. Upload your own images for prediction  

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
