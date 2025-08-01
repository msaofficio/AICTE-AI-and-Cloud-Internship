# AICTE-AI-and-Cloud-Internship

# ⚡ Power System Fault Detection and Classification Using Machine Learning

This project is focused on detecting and classifying different types of faults in a power distribution system using machine learning. It uses voltage and current phasor data to distinguish between normal operation and fault conditions such as Line-to-Ground (L-G), Line-to-Line (L-L), and Three-Phase faults.

The model was built using **IBM Watsonx.ai AutoAI**, trained on a public Kaggle dataset, and deployed on **IBM Cloud Lite** for real-time testing.

---

## 📊 Problem Statement

Fault detection in power systems is critical for grid stability and reliability. Traditional methods are slow and reactive. This project proposes an ML-based solution that can rapidly and accurately detect faults from live system parameters.

---

## 📁 Dataset

- Source: [Kaggle - Power System Faults Dataset](https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset)
- Format: CSV
- Preprocessing: Data Refinery on IBM Watsonx.ai
- Columns used: `Type`, `Air temperature`, `Process temperature`, `Rotational speed`, `Torque`, `Tool wear`, `Target`
- Dropped: `UDI`, `Product ID`

---

## 🧠 ML Model

- Built using: IBM Watsonx.ai AutoAI
- Algorithm used: Snap Random Forest Classifier
- Accuracy: **99.4%**
- Feature Engineering + Hyperparameter Optimization included
- Trained with Cross-Validation
- Final model deployed on IBM Cloud

---

![Model Prediction Screenshot](./images/test_result%202.png)


