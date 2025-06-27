
# 🔐 Quantum Machine Learning for Cybersecurity & PKI

This repository contains **hands-on Google Colab notebooks** using real QML frameworks to solve security problems like trust scoring, anomaly detection, and cryptographic pattern classification. A synthetic PKI dataset is included for experimentation.

## 📁 Contents

| File                               | Description                                                |
|------------------------------------|------------------------------------------------------------|
| synthetic_pki_dataset.csv          | Synthetic dataset simulating PKI certificate trust factors |
| qiskit_pki_qml_notebook.ipynb      | QSVC (Quantum SVM) using Qiskit Machine Learning           |
| tfq_pki_qml_notebook.ipynb         | Quantum Neural Network using TensorFlow Quantum (TFQ)      |
| pennylane_pki_qml_notebook.ipynb   | Hybrid quantum-classical classifier using PennyLane        |

## 📊 Dataset Overview

Each row simulates a digital certificate with the following fields:
- cert_expiry_days
- signature_algorithm (SHA256=2, SHA1=1, MD5=0)
- key_length
- revocation_status
- trusted_CA
- label (1 = Trusted, 0 = Untrusted)

## 🧠 QML Notebooks

### 📘 qiskit_pki_qml_notebook.ipynb
Uses a **Quantum Support Vector Classifier (QSVC)** with a ZZFeatureMap kernel. Ideal for cryptographic pattern detection.

### 📘 tfq_pki_qml_notebook.ipynb
Builds a **Quantum Neural Network** using TensorFlow Quantum. Demonstrates adaptive trust modeling with a single-qubit PQC.

### 📘 pennylane_pki_qml_notebook.ipynb
Trains a hybrid variational quantum circuit for binary classification. Good intro to VQCs in security applications.

## ✅ How to Use

1. Open any notebook in Google Colab
2. Install required libraries
3. Run each block and observe training results

## 🚀 Future Extensions

- Real PKI logs integration
- More features for deep trust modeling
- Run on real quantum hardware
