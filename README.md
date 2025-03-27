# Cybersecurity-Threat-Classification-Using-Machine-Learning
# Cybersecurity Threat Classification

## Project Overview
Machine learning project for classifying cybersecurity threats using network flow data with multiple ML models.

## Requirements
- Python 3.8+
- Libraries: 
  ```
  pandas
  numpy
  scikit-learn
  matplotlib
  seaborn
  imbalanced-learn
  ```

## Installation
```bash
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn
```

## Running the Project
1. Ensure you have the dataset `TestbedMonJun14Flows.csv`
   link: https://www.unb.ca/cic/datasets/ids.html
3. Run the Jupyter notebook or Python script
4. The script will:
   - Preprocess the data
   - Train multiple ML models
   - Generate performance metrics and confusion matrices

## Model Performance
Evaluates performance of:
- K-Nearest Neighbors
- Decision Tree
- Logistic Regression
- Random Forest

## Key Preprocessing Steps
- Missing value handling
- Outlier removal
- Feature engineering
- Class balancing with SMOTE
