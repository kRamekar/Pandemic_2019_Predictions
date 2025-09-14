# Pandemic_2019_Predictions

## Overview
This project focuses on analysing COVID-19 data to build predictive models that can aid in the early detection or forecasting of COVID-19 infections. The analysis is carried out using Python, leveraging essential libraries for data manipulation, visualisation, and machine learning and algorithms.

## Project Structure
The notebook is organized into several distinct sections, each dedicated to a specific aspect of the workflow:

1. **Importing Packages**: Relevant Python libraries such as NumPy, pandas, Matplotlib, seaborn, and scikit-learn are imported for performing data analysis, visualisation, and machine learning tasks.

2. **Data Loading**: The data is uploaded into a pandas DataFrame from an Excel file (dataset.xlsx). Ensure the file is placed in the same directory as the notebook, or adjust the path to where the file is stored.

3. **Exploratory Data Analysis (EDA)**: Initial exploration of the dataset is conducted to understand its features, data types, missing values, and other preliminary insights through visualisations.

4. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Standardizing numerical variables

5. **Feature Engineering**: Selection and creation of relevant features based on the exploratory analysis.

6. **Model Building**:
   - Data split into training and testing sets.
   - Use of classification algorithms such as Logistic Regression, Decision Trees, or Random Forest (based on the notebook content).

7. **Model Evaluation**:
   - Performance metrics such as accuracy, precision, recall, ROC-AUC, and F1 score.
   - Confusion matrix and ROC curves for visual performance evaluation.

## Dataset
The project uses an Excel dataset (`dataset.xlsx`). This file must contain relevant COVID-19 patient or case data, including features that aid in prediction, such as demographic information, symptoms, pre-existing conditions, or clinical findings.

## Running the Project

### Requirements
- Python (version >= 3.6)
- Libraries: pandas, NumPy, Matplotlib, seaborn, scikit-learn

Install the libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Steps
1. Place `dataset.xlsx` in the same directory as your Jupyter Notebook.
2. Execute the notebook sequentially to replicate the results.
3. Modify and experiment with different models or preprocessing methods to potentially improve prediction accuracy.

## Modifying the Project
- **Dataset Update**: Replace or update `dataset.xlsx` with new data or expanded datasets.
- **Model Adjustments**: Experiment with different algorithms, hyperparameters, or cross-validation techniques.
- **Feature Changes**: Include or remove features to test impacts on model performance.

## Contributions
Feel free to clone, fork, and improve upon this project. Contributions for better accuracy, code optimization, or feature engineering improvements are welcome.

---

**Author:** Kaustubh Ramekar

**Date:** 10/05/2025
---
