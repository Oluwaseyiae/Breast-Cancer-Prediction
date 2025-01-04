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

---

## Key Steps

1. **Data Preprocessing**: Cleaning, scaling, and handling missing values.  
2. **Model Training**: Training multiple machine learning classifiers.  
3. **Evaluation**: Using Confusion Matrices and Accuracy Scores to assess performance.

---

## Usage

1. **Clone this Repository**:  
   ```bash
   git clone https://github.com/Oluwaseyiae/Breast-Cancer-Prediction.git
   
2. **Install Required Libraries**:

```bash
pip install numpy
pip install pandas
pip install sklearn
```
---

### Insights
- Multiple machine learning models demonstrated high accuracy in predicting breast cancer.
- **Logistic Regression**, **Kernel SVM**, **K-Nearest Neighbors**, and **Decision Tree** models achieved the highest accuracy of **95.62%**.
- The results highlight the potential of machine learning in assisting early detection and diagnosis.
- Models like **Random Forest** and **Naive Bayes**, though slightly less accurate, still provided meaningful insights into the dataset.

---

### Future Work
- **Deep Learning**: Explore neural network architectures (e.g., CNN, MLP) to further improve prediction accuracy.
- **Feature Engineering**: Experiment with advanced feature selection or transformation techniques to enhance model performance.
- **Dataset Expansion**: Integrate additional diagnostic data or diverse datasets to build more robust models.
- **Deployment**: Develop a user-friendly web or mobile app to deploy the best-performing model for real-world use.

---

### Contributions
Contributions to this project are highly encouraged! Here's how you can contribute:

- **Fork the Repository**: Click the "Fork" button at the top of this page.
- **Clone Your Forked Repository**:
  ```bash
  git clone https://github.com/oluwaseyiae/Breast-Cancer-Prediction.git

**Create a New Branch**:
- To start working on a new feature or bug fix, create a new branch from your local repository:
  ```bash
  git checkout -b feature-name

**Commit Your Changes**:
- After making the necessary changes, commit them with a descriptive message:
  ```bash
  git commit -m "Describe the changes you made"

**Push Your Changes**:
- Push the changes to your remote repository (GitHub):
  ```bash
  git push origin feature-name
