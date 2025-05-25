# 🩺 Evaluation of Diagnostic Models

### 📍 Course Project – *AI for Medical Diagnosis* by DeepLearning.AI on Coursera

This project is part of the *AI for Medical Diagnosis* specialization (Week 2) taught by Andrew Ng.  
It focuses on **evaluating deep learning models for medical imaging**, specifically the model developed for chest X-ray classification.

---

## 🧠 Key Concepts Practiced

- ✅ Evaluation metrics for medical diagnostics:
  - Accuracy, Sensitivity, Specificity
  - PPV (Positive Predictive Value), NPV (Negative Predictive Value)
  - ROC Curve & AUC
  - F1 Score & Confidence Intervals
  - Calibration and Platt Scaling
- ✅ Implementation of core functions using NumPy
- ✅ ROC and PRC visualizations using `sklearn`
- ✅ Bootstrapping to calculate 95% confidence intervals
- ✅ Model calibration using logistic regression (Platt scaling)

---

## 🛠️ Tools & Libraries

- Python 3
- NumPy / Pandas
- Scikit-learn
- Matplotlib
- Coursera-provided utilities (`util.py`, `test_utils.py`)

---

## 📁 Repo Contents

- `C1_W2_Assignment.ipynb`: Main notebook with all implementations and plots
- `C1_W2_Assignment.pdf`: Static version for preview
- `util.py`: Utility functions (e.g. ROC, PRC, GradCAM visualization)
- `test_utils.py`: Functions used for automated testing
- `data/`: CSVs of precomputed model predictions and labels (optional)

---

## ⚠️ Disclaimer

> 📌 This notebook is part of the official Coursera course:  
> [AI for Medical Diagnosis – by DeepLearning.AI](https://www.coursera.org/learn/ai-for-medical-diagnosis)  
> It is intended **for educational and portfolio purposes only**.  
> **Do not plagiarize or submit as your own work** on Coursera or any academic platform.

---

## 📊 Example Output

You’ll find ROC curves, precision-recall curves, calibration plots, and metric tables for 14 chest pathologies including:
- Cardiomegaly
- Emphysema
- Edema
- Pneumonia
- Consolidation
…and more.

---

## 📌 Related Projects
- [Chest X-Ray Medical Diagnosis with Deep Learning]([https://github.com/yianmast/Chest-XRay-Diagnosis](https://github.com/yianmast/Chest-XRay-Diagnosis-deep-learning))
