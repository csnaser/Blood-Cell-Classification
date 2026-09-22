# Blood-Cell-Classification


# 🔬 Blood Cell Classification using PyTorch

An end-to-end Deep Learning project for multi-class classification of peripheral blood cell images using PyTorch. The model identifies and categorizes microscopic blood cells into four distinct diagnostic classes.

---

##  Project Overview
Automated identification of blood cell subtypes is vital for accelerating diagnostic workflows in hematology and clinical pathology. This project implements a Convolutional Neural Network (CNN) pipeline to classify single-cell microscopic images into:

- **Eosinophils**
- **Lymphocytes**
- **Monocytes**
- **Neutrophils**

---

##  Tech Stack & Tools
- **Framework:** PyTorch & Torchvision
- **Data Manipulation & Metrics:** NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Python 3.10+

---

##  Architecture & Pipeline
1. **Preprocessing & Augmentation:** Applied random rotations, flips, color jitter, and normalization to improve model generalization.
2. **Model Architecture:** Custom CNN / Transfer Learning backbone trained using Cross-Entropy Loss and Adam optimizer.
3. **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, and Confusion Matrix analysis across all classes.

---

##  Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/blood-cell-classification.git](https://github.com/your-username/blood-cell-classification.git)
cd blood-cell-classification
