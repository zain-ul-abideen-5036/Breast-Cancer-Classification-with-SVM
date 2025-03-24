# Breast Cancer Classification with SVM

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-brightgreen)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-lightgrey)

A machine learning project that uses Support Vector Machines (SVM) to classify breast cancer tumors as malignant or benign, achieving 98.25% accuracy.

---

## Features
- Data loading and exploration
- Feature visualization using histograms
- Data preprocessing with StandardScaler
- SVM model implementation with RBF kernel
- Model evaluation using classification report and confusion matrix
---

## Dataset
The Wisconsin Breast Cancer Diagnostic Dataset from scikit-learn:
- 569 samples (357 benign, 212 malignant)
- 30 numeric features computed from digitized images
- Target classes: Malignant (0) and Benign (1)
---

## Code Structure
1. Data Loading and Preparation
2. Data Preprocessing (Train-Test Split, Scaling)
3. Feature Distribution Visualization
4. SVM Model Implementation
5. Model Evaluation
---

## Installation
1. Clone repository:
```bash
git clone https://github.com/YOUR-USERNAME/breast-cancer-classification.git
cd breast-cancer-classification
```
2. Install requirements:
```bash
pip install -r requirements.txt
```
---

## Usage
1. Start Jupyter Notebook:
```
jupyter notebook notebooks/Breast_Cancer_Classification.ipynb
```
2. Open ```Breast_Cancer_Classification.ipynb```
3. Run cells sequentially to:
   - Load and preprocess data
   - Train SVM model
   - Evaluate performance
   - Visualize results
---

## Results
- Accuracy: 98.25%
- Precision (Malignant): 100%
- Recall (Benign): 100%
- **Confusion Matrix:**
  
|                | **Predicted Malignant** | **Predicted Benign** |
|----------------|:-----------------------:|:--------------------:|
| **Actual Malignant** | 41                | 2                    |
| **Actual Benign**    | 0                 | 71                   |
---

## Contributing
- Fork the repository
- Create feature branch
- Submit PR with detailed description
---

## Contact
For questions or feedback, contact: abideen5036@gmail.com

---

