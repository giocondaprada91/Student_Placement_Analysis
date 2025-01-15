# Programming for Analysis: Student Placement Analysis

## Overview
This project was created as part of my **Programming for Analysis** class at **Baruch College**. The goal was to analyze and predict the placement status of students based on their academic and demographic data. It involved data preprocessing, visualization, and logistic regression modeling to uncover patterns and make predictions.

---

## Dataset
The dataset `Placement.csv` contains 215 student records with the following columns:
- **Demographics**: Gender, work experience.
- **Academic Performance**: SSC percentage, HSC percentage, degree percentage.
- **Specialization**: Marketing and Finance (Mkt&Fin), Marketing and Human Resources (Mkt&HR).
- **Placement Details**: Salary and placement status (Placed/Not Placed).

---

## Objectives
1. Clean and preprocess the dataset by addressing missing values and outliers.
2. Perform data visualization to extract meaningful insights.
3. Develop and evaluate a logistic regression model to predict placement status.

---

## Key Features
### 1. **Data Cleaning**
- Missing values for categorical columns were filled with the mode, and for numerical columns, with the median.
- Outliers were detected and handled using the Interquartile Range (IQR) method.

### 2. **Visualizations**
- Distribution of academic performance metrics.
- Placement status by work experience.
- Specialization analysis (Mkt&Fin vs. Mkt&HR).
- Correlation heatmap of academic performance metrics and salary.

### 3. **Predictive Modeling**
- Encoded categorical variables using one-hot encoding.
- Built a logistic regression model using Scikit-learn.
- Evaluated performance using accuracy scores and confusion matrices.

---

## Results
- **Model Accuracy**: 83.6% on the test set.
- **Insights**:
  - Students without prior work experience had higher placement rates.
  - Marketing and Finance specialization (Mkt&Fin) showed higher placement success compared to Marketing and Human Resources (Mkt&HR).
  - Students with higher SSC percentages tended to have better placement outcomes.

---

## Repository Structure
```
Programming_for_Analysis_Project/
├── data/
│   └── Placement.csv               # Dataset
├── notebooks/
│   └── placement_analysis.ipynb    # Jupyter Notebook with the analysis
├── visuals/
│   ├── academic_performance.png    # Visualization 1
│   ├── placement_by_workex.png     # Visualization 2
│   └── correlation_heatmap.png     # Visualization 3
└── README.md                       # Project description
```

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Scikit-learn
- **Tools**: Jupyter Notebook

---

## Acknowledgment
This project was completed as part of my coursework for the **Programming for Analysis** class at **Baruch College**. It reflects my learning journey and application of programming concepts to solve real-world problems.
