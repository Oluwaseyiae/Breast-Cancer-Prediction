# Breast Cancer Prediction

## Overview
Breast cancer is a significant health concern, and early diagnosis plays a vital role in improving treatment outcomes. This project utilizes machine learning models to predict the presence of breast cancer based on diagnostic data.

---

## Dataset
- **Source**: Kaggle  
- **Features**: Diagnostic attributes related to breast cancer  
- **Target Variable**: Binary classification (presence or absence of breast cancer)  

---

## Models and Performance

| **Model**               | **Confusion Matrix**      | **Accuracy Score** |
|--------------------------|---------------------------|---------------------|
| **Kernel SVM**           | `[[82, 5], [1, 49]]`     | **0.9562**          |
| **SVM**                  | `[[83, 4], [2, 48]]`     | **0.9562**          |
| **Random Forest**        | `[[83, 4], [3, 47]]`     | 0.9489              |
| **Logistic Regression**  | `[[84, 3], [3, 47]]`     | **0.9562**          |
| **K-Nearest Neighbors**  | `[[83, 4], [2, 48]]`     | **0.9562**          |
| **Decision Tree**        | `[[84, 3], [3, 47]]`     | **0.9562**          |
| **Naive Bayes**          | `[[80, 7], [0, 50]]`     | 0.9400              |

### Best Model(s)
- **Kernel SVM**, **SVM**, **Logistic Regression**, **K-Nearest Neighbors**, and **Decision Tree** achieved the highest accuracy of **95.62%**.

---

## Tools and Technologies
- **Programming Language**: Python  
- **Libraries Used**:
  - Scikit-learn  
  - NumPy, Pandas  
  - Matplotlib, Seaborn (for visualizations, if applicable)

---

## Key Steps

1. **Data Preprocessing**: Cleaning, scaling, and handling missing values.  
2. **Model Training**: Training multiple machine learning classifiers.  
3. **Evaluation**: Using Confusion Matrices and Accuracy Scores to assess performance.

---

## Usage

1. **Clone this Repository**:  
   ```bash
   git clone https://github.com/YourUsername/Breast-Cancer-Prediction.git
