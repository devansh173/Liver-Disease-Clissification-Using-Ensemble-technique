# Liver Disease Classification using ensemble technique

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Objective](#objective)
4. [Technologies Used](#technologies-used)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Results](#results)


---

## Introduction

Liver disease is a significant global health issue. This project aims to analyze and predict the likelihood of liver disease based on patient data using machine learning and statistical analysis.

By leveraging medical datasets and predictive modeling, this project seeks to assist healthcare professionals in identifying high-risk patients and making informed decisions.

---

## Dataset

The dataset used for this project includes clinical and biochemical data of patients, such as:
- Age
- Gender
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphatase
- Alanine Aminotransferase (ALT)
- Aspartate Aminotransferase (AST)
- Total Proteins
- Albumin
- A/G Ratio (Albumin/Globulin ratio)

**Source**: [https://www.kaggle.com/datasets/abhi8923shriv/liver-disease-patient-dataset].

---

## Objective

- To perform exploratory data analysis (EDA) to uncover patterns in the data.
- To build machine learning models to predict the presence of liver disease.
- To evaluate model performance and provide insights for clinical applications.

---

## Technologies Used

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - Pandas, NumPy: For data manipulation and analysis
  - Matplotlib, Seaborn: For data visualization
  - Scikit-learn: For machine learning models
  - XGBoost: For advanced model tuning
  - Flask/Django (Optional): For creating a web-based interface
- **Tools**: Jupyter Notebook, Git

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/liver-disease-prediction.git
   cd liver-disease-prediction
`
2.Create and activate a virtual environment:
```bash
  python -m venv env
  source env/bin/activate  # For Linux/Mac
  env\Scripts\activate  # For Windows
````

## Usage

Follow these steps to use this project:
Open the Jupyter Notebook:
```bash

jupyter notebook
````
Navigate to the EDA and modeling notebooks to explore the data and train the models.
(Optional) Run the Flask/Django application:
```bash

python app.py``
````

## Results

The models achieved the following performance:


| Model                | Accuracy | F1 Score |
|----------------------|----------|----------|
| Logistic Regression  | 72%      | 56%      |
| Random Forest        | 99%      | 99%      |
| XGBoost              | 72%      | 63%      |

as you can see there is a overfitting problem with Random Forest

### Key Visualizations

#### 1. ROC Curves
The Receiver Operating Characteristic (ROC) curve compares the true positive rate (sensitivity) and the false positive rate (1-specificity) for each model.

![image](https://github.com/user-attachments/assets/6eb3bbd5-1538-408b-9970-78b64e2f6782)


#### 2. Confusion Matrices
Confusion matrices visualize the performance of classification models by showing the count of true positives, true negatives, false positives, and false negatives.

<img width="366" alt="image" src="https://github.com/user-attachments/assets/c893e80b-cc84-4521-908b-965a2fab5e0e">


#### 3. Feature Importance
The most influential features for predicting liver disease, as identified by the Random Forest and XGBoost models.

![image](https://github.com/user-attachments/assets/b4606e94-440e-419f-bfea-994fe6493fd1)


#### 4. Final Result
![image](https://github.com/user-attachments/assets/898dbd79-5a69-45d3-ab88-b88108aec25b)

---

## Contact

For any queries or doubts regarding this project, feel free to contact me at:

📧 **Email**: [bdevansh173@gmail.com](mailto:bdevansh173@gmail.com)


