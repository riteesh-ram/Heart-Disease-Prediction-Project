# Heart Disease Prediction Project

## Overview
This project uses real patient data and machine learning to predict the likelihood of heart disease. It is designed to help both technical and non-technical audiences understand how data science can be applied to healthcare problems. The project includes data analysis, visualizations, and several predictive models, all documented in a Jupyter notebook and a project report.

## Why This Project Matters
Heart disease is a leading cause of death worldwide. Early prediction can save lives and reduce healthcare costs. This project demonstrates how modern data analytics and machine learning can support medical decision-making.

## Dataset Description
The dataset contains information about patients, including:
- **age:** Age in years
- **sex:** Male or female
- **cp:** Type of chest pain
- **trestbps:** Resting blood pressure
- **chol:** Cholesterol level
- **fbs:** High fasting blood sugar (yes/no)
- **restecg:** ECG results
- **thalach:** Maximum heart rate achieved
- **exang:** Exercise-induced angina (yes/no)
- **oldpeak:** ST depression after exercise
- **slope:** Slope of peak exercise ST segment
- **ca:** Number of major vessels colored by fluoroscopy
- **thal:** Thalassemia type
- **target:** Presence of heart disease (yes/no)

## File Directory Structure
```
├── 2018_CSE_Heart Disease Prediction_Bollavaram Golla Riteesh Ram Chander.pdf   # Project report
├── heart dataset.csv                                                            # Heart disease dataset (UCI)
├── Heart_Disease_Prediction_BDA_Project_.ipynb                                  # Main Jupyter notebook
```

## What Does the Project Do?
- **Data Loading & Cleaning:** Reads and prepares the heart disease dataset for analysis.
- **Exploratory Data Analysis (EDA):** Visualizes and explains patterns in the data, making it easy to see which factors are linked to heart disease.
- **Feature Engineering:** Transforms data to make it suitable for machine learning.
- **Model Building:** Trains and compares several machine learning models:
  - Logistic Regression
  - Naive Bayes
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest
- **Model Evaluation:** Measures how well each model predicts heart disease using accuracy and confusion matrices.
- **Visualization:** Shows results and important patterns with easy-to-understand charts.
- **Model Comparison:** Helps select the best model for heart disease prediction.
- **Documentation:** Includes a detailed project report (PDF) for further reading.

## How to Set Up and Run
1. **Clone the Repository**
   ```bash
   git clone <repo-url>
   cd Data-Analytics-and-Model-Predictions-on-Heart-Diseases
   ```
2. **Install Python & Dependencies**
   - Make sure you have Python 3.x installed.
   - Install required packages:
     ```bash
     pip install pandas numpy matplotlib seaborn scikit-learn scikit-plot jupyter
     ```
3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook Heart_Disease_Prediction_BDA_Project_.ipynb
   ```
   - Open the notebook and run each cell in order. The notebook will guide you through the analysis and model building steps.


## Project Report
- The PDF file provides a written summary of the project, including background, methodology, and results.

## Author
- Bollavaram Golla Riteesh Ram Chander

## Contributing
Suggestions are welcome. Please open an issue or submit a pull request.
