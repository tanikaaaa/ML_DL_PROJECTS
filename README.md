# 🧠 Machine Learning — Algorithms & Evaluation Tools (From Scratch in Python)

Welcome to this curated collection of classic **Machine Learning algorithms** and **model evaluation tools**, all implemented **from scratch** using **Python** and **Jupyter Notebooks**.

This repo is ideal for students, enthusiasts, and developers who want to understand the **mathematics and logic** behind ML.

---

## 🧾 Overview

🔹 Supervised & Unsupervised Learning  
🔹 Dimensionality Reduction  
🔹 Model Evaluation Metrics  
🔹 Visualization Tools  
🔹 Data Preprocessing & Utility Functions  
🔹 **Deep Learning & Generative Models (GANs)**  

Each topic is available as:
- 📜 `.py` scripts — clean, modular code
- 📒 `.ipynb` notebooks — interactive and visual explanations

---

## 💡 Part 1: Machine Learning Algorithms

### 🔍 Supervised Learning
| Algorithm                    | Script                          | Notebook                          |
|-----------------------------|----------------------------------|-----------------------------------|
| Linear Regression           | `linear_regression.py`          | `LINEAR_REGRESSION.ipynb`         |
| Ridge Regression            | `ridge_regression.py`           | `RIDGE_REGRESSION.ipynb`          |
| Logistic Regression         | `logistic.py`                   | `LOGISTIC.ipynb`                  |
| Perceptron                  | `perceptron.py`                 | `PERCEPTRON.ipynb`                |
| K-Nearest Neighbors (KNN)   | `knn.py`                        | `KNN.ipynb`                        |
| Naive Bayes Classifier      | `naive_bayes_classifier.py`     | `NAIVE_BAYES_CLASSIFIER.ipynb`    |
| Mahalanobis Distance Classifier | `mahalanobis_distance_classifier.py` | `MAHALANOBIS_DISTANCE_CLASSIFIER.ipynb` |
| Euclidean Distance Classifier  | `euclidean_distance_classifier.py` | `EUCLIDEAN_DISTANCE_CLASSIFIER.ipynb` |

---

### 🧭 Unsupervised Learning
| Algorithm                 | Script                            | Notebook                           |
|--------------------------|------------------------------------|------------------------------------|
| K-Means Clustering       | `k_means_clustering.py`            | `K_MEANS_CLUSTERING.ipynb`         |
| Single Linkage Clustering| `single_linkage_clustering.py`     | `SINGLE_LINKAGE_CLUSTERING.ipynb`  |
| Complete Linkage Clustering | `complete_linkage_clustering.py` | `COMPLETE_LINKAGE_CLUSTERING.ipynb`|

---

### 📉 Dimensionality Reduction
| Algorithm        | Script                          | Notebook                            |
|------------------|----------------------------------|-------------------------------------|
| Principal Component Analysis (PCA) | `principal_component_analysis.py` | `PRINCIPAL_COMPONENT_ANALYSIS.ipynb` |

---

## 🧪 Part 2: Model Evaluation & Statistical Tools

### 📈 Evaluation & Performance
- `evaluation_metrics.py` / `EVALUATION_METRICS.ipynb`  
  → Accuracy, Precision, Recall, F1 Score, ROC-AUC  
- `evaluation_metrics_2.py` / `EVALUATION_METRICS_2.ipynb`  
  → DET & ROC Curves, AUC Calculation  

### 🧮 Confusion Matrices
- `confusion_matrix(two_class).py` / `CONFUSION_MATRIX(TWO_CLASS).ipynb`  
- `confusion_matrix_(multiclass).py` / `CONFUSION_MATRIX_(MULTICLASS).ipynb`  
  → Visual and numeric confusion matrix analysis  

### 🔁 Cross Validation
- `k_fold_cross_validation.py` / `K_FOLD_CROSS_VALIDATION.ipynb`  
  → Manual K-Fold implementation  

### 📉 Error Visualization
- `plot_errors.py` / `PLOT_ERRORS.ipynb`  
  → Visual comparison of predicted vs actual  

---

### 📊 Statistical Utilities
- `covariance_matrix.py` / `COVARIANCE_MATRIX.ipynb`  
- `gaussian_(univariate).py` / `GAUSSIAN_(UNIVARIATE).ipynb`  
- `gaussian_(multivariate).py` / `GAUSSIAN_(MULTIVARIATE).ipynb`  
  → Core statistical functions for analysis  

### 🔀 Data Splitting
- `training_and_testing_set(splitting).py` / `TRAINING_AND_TESTING_SET(SPLITTING).ipynb`  
  → Manual train-test split logic  

---

## 🤖 Part 3: Deep Learning — Generative Adversarial Networks (DCGAN)

This repository also includes a **Deep Learning project** focused on **Generative Adversarial Networks (GANs)** for **realistic human face generation**.

### 🧠 DCGAN – Human Face Generation
- Implemented a **Deep Convolutional GAN (DCGAN)** architecture consisting of:
  - Generator network using transposed convolution layers
  - Discriminator network using deep convolution layers
- Trained the model using **adversarial learning** to generate realistic human face images from random noise
- Explored training stability techniques and loss behavior during generator–discriminator competition
- Gained hands-on experience with **deep learning workflows, convolutional architectures, and generative modeling**

This project bridges **classical ML fundamentals** with **modern deep learning and computer vision techniques**.

---

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/tanikaaaa/MACHINE-LEARNING.git
cd MACHINE-LEARNING
