# Employee Attrition Prediction Project

## 📋 Project Overview

This project aims to **predict employee turnover** using machine learning techniques, helping HR departments identify **risk factors** and **develop strategies** to retain talent. By understanding the factors contributing to employee attrition, organizations can take proactive measures to reduce turnover and improve employee satisfaction.

## 📂 Dataset

The dataset used in this project is a **fictional employee attrition dataset** created by IBM data scientists. The dataset includes various employee attributes, such as job role, monthly income, years at the company, work-life balance, and more.

- **Data Source:** IBM Sample Dataset
- **Target Variable:** `Attrition` (whether an employee has left the company)

## 💻 Project Workflow

1. **Data Cleaning & Preprocessing**  
   - Checked for missing values and outliers.
   - Encoded categorical variables.
   - Scaled numerical features for improved model performance.

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed distributions of key features.
   - Visualized relationships between features and attrition.
   - Identified potential risk factors for employee turnover.

3. **Model Selection & Evaluation**  
   - Tested multiple machine learning algorithms:
     - **Logistic Regression**
     - **Random Forest**
     - **Gradient Boosting**
     - **Support Vector Machine**
     - **Neural Network**
   - Evaluated each model using **accuracy**, **F1 score**, and **ROC AUC** metrics.
   - Selected **Logistic Regression** as the final model due to its balance of interpretability and performance.

4. **Feature Importance Analysis**  
   - Identified top factors contributing to attrition, including job role, monthly income, and work-life balance.
   - Visualized feature importance to help HR teams focus on actionable areas.

5. **Results Visualization**  
   - Created visualizations to illustrate model performance and key attrition factors.
   - **Bar charts** comparing accuracy, F1 score, and ROC AUC for each model.
   - **Feature importance chart** showcasing the top drivers of turnover.
   - **Pie chart** displaying the overall attrition rate.

## 📊 Key Insights

- **Top Factors Influencing Attrition:**  
  The analysis identified several critical factors influencing employee attrition, including:
  - **Job Role**
  - **Monthly Income**
  - **Work-Life Balance**

- **Actionable Insights for HR:**  
  By focusing on these high-impact areas, HR departments can:
  - Develop targeted retention strategies for high-risk roles.
  - Explore adjustments to income structures or work-life balance policies.

## 🚀 Getting Started

To run this project locally, follow these steps:

### Prerequisites

Ensure you have the following installed:
- **Python 3.6+**
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/avinishaaa/employee-attrition-prediction.git
   cd employee-attrition-prediction
