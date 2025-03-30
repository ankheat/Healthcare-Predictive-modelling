# Predictive Modeling for Patient Readmission

## Overview
This project focuses on building a predictive model to determine whether a patient is likely to be readmitted to the hospital. The goal is to identify high-risk patients, minimize missed readmissions, and provide actionable insights for hospital decision-making. The workflow includes data loading, exploration, preprocessing, feature engineering, model training, and evaluation.

## Project Structure

### 1. Importing Libraries and Loading Data
- Imported necessary Python libraries for data manipulation, visualization, feature selection, model training, and evaluation.
- Loaded the dataset and examined its structure.
- Checked for missing values and data types.

### 2. Data Exploration
- Performed an initial analysis of the dataset.
- Identified missing values and examined summary statistics of numerical features.

### 3. Data Preprocessing
- Encoded categorical variables using label encoding and one-hot encoding.
- Scaled numerical features to ensure consistency in model training.
- Handled missing values appropriately.

### 4. Feature Importance
- Identified important features using statistical methods such as correlation matrix and Random Forest.
- Reduced dimensionality by selecting the most relevant features.

### 5. Model Training and Evaluation
- Trained multiple machine learning models to predict patient readmission.
- Evaluated models using appropriate performance metrics.
- Compared model performances to determine the best-performing algorithm.

## Technologies Used
- Python
- Pandas, NumPy (Data Manipulation)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-learn (Machine Learning & Model Evaluation)
- Random Forest (Feature Selection & Prediction)

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/ankheat/Healthcare-Predictive-modelling.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Healthcare-Predictive-modelling
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook to execute the workflow.

## Future Improvements
- Incorporate deep learning techniques for better prediction accuracy.
- Experiment with additional feature engineering techniques.
- Deploy the model as a web-based application for real-time predictions.

## License
This project is open-source and available under the MIT License.

