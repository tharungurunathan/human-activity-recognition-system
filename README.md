# Human Activity Recognition System using Machine Learning

<p align="center">
  <b>Sensor-Based Human Activity Classification using Classical Machine Learning Techniques</b>
</p>

<p align="center">
  Python • Scikit-learn • PCA • Random Forest • Extra Trees • Ridge Classifier
</p>

---

# Overview

This project presents a Human Activity Recognition (HAR) system developed using machine learning techniques on smartphone sensor data.

The study focuses on classifying human activities using accelerometer and gyroscope measurements collected from wearable devices. Multiple machine learning models and dimensionality reduction techniques were evaluated to investigate classification performance, computational efficiency, and feature-space optimization.

The project was developed as part of academic coursework in machine learning and data science.

---

# Objectives

The main objectives of this project were:

- Build an activity recognition pipeline using sensor data
- Compare multiple machine learning classifiers
- Investigate the impact of dimensionality reduction using PCA
- Evaluate classification accuracy across activities
- Analyse computational efficiency and model performance

---

# Dataset

The project uses the **UCI Human Activity Recognition Dataset**, which contains smartphone sensor signals collected from participants performing daily activities.

## Activities Classified

- Walking
- Walking Upstairs
- Walking Downstairs
- Sitting
- Standing
- Laying

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| NumPy | Numerical Computation |
| Pandas | Data Processing |
| Scikit-learn | Machine Learning |
| Matplotlib | Visualization |
| Seaborn | Data Visualization |
| Jupyter Notebook | Experimentation |

---

# Machine Learning Pipeline

The project follows the workflow below:

1. Data Loading
2. Data Cleaning
3. Feature Scaling
4. Dimensionality Reduction (PCA)
5. Model Training
6. Model Evaluation
7. Performance Comparison

---

# Models Evaluated

The following machine learning models were implemented and compared:

| Model | Purpose |
|---|---|
| Random Forest | Ensemble-based classification |
| Extra Trees Classifier | Randomized tree ensemble |
| Ridge Classifier | Linear classification baseline |

---

# Dimensionality Reduction

Principal Component Analysis (PCA) was applied to reduce feature dimensionality and investigate how lower-dimensional representations affect classification performance.

The study evaluates:
- Classification accuracy
- Computational efficiency
- Feature compression effectiveness

---

# Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# Key Findings

- Ensemble-based models achieved strong classification performance across activities.
- PCA reduced feature dimensionality while maintaining competitive accuracy.
- Random Forest and Extra Trees demonstrated robust performance on sensor-based activity classification tasks.
- Dimensionality reduction improved computational efficiency without significant performance degradation.

---

# Repository Structure

```bash
human-activity-recognition-system/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── human_activity_recognition.ipynb
│
├── reports/
│   └── HAR_Report.pdf
│
├── presentation/
│   └── HAR_Presentation.pdf
```

---

# How to Run

## 1. Clone Repository

```bash
git clone https://github.com/tharungurunathan/human-activity-recognition-system.git
```

---

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3. Launch Notebook

```bash
jupyter notebook
```

Open:

```bash
notebooks/human_activity_recognition.ipynb
```

---

# Requirements

```txt
numpy
pandas
matplotlib
scikit-learn
seaborn
jupyter
scipy
```

---

# Future Improvements

Potential future enhancements include:

- Deep learning-based HAR models
- CNN/LSTM architectures
- Real-time activity recognition
- Mobile deployment
- Hyperparameter optimization
- Sensor fusion techniques

---

# Academic Context

This project was developed for academic coursework focused on machine learning and activity recognition using wearable sensor data.

The work includes:
- model experimentation
- dimensionality reduction analysis
- comparative classifier evaluation
- performance visualization

---

# Author

## Tharun Gurunathan

GitHub:
https://github.com/tharungurunathan

---

# License

This project is intended for academic and educational purposes.
