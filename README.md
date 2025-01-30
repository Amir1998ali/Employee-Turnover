# Employee Turnover Prediction

## Overview
This project builds a **machine learning pipeline** to predict employee turnover, identify high-risk employees, and optimize workforce retention strategies. It leverages **data preprocessing, feature engineering, and model optimization techniques** to enhance prediction accuracy and efficiency.

## Features
- **Data Preprocessing**: Cleans and balances the dataset using **SMOTE** to handle class imbalances.
- **Feature Engineering**: Applies **K-Means clustering** to segment employees into different risk zones.
- **Machine Learning Models**: Implements **Logistic Regression, Random Forest, and Gradient Boosting** for turnover prediction.
- **Optimization Techniques**: Uses **Stratified K-Fold cross-validation** to improve model generalization and performance.
- **Performance Evaluation**: Measures **accuracy, precision, recall, and AUC scores** to assess model effectiveness.

## Technologies Used
- **Python** (pandas, NumPy, Scikit-learn, imbalanced-learn, Matplotlib, Seaborn)
- **Machine Learning** (Logistic Regression, Random Forest, Gradient Boosting, K-Means Clustering)
- **Pipeline & Data Processing** (SMOTE for balancing, StandardScaler for normalization, K-Fold validation)

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/Amir1998ali/Employee-Turnover.git
   cd Employee-Turnover
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```

## Usage
- Load the dataset and preprocess the data.
- Train and evaluate different models.
- Use clustering to analyze high-risk employee groups.
- Optimize and fine-tune models for better accuracy.

## Results
- Successfully predicted employee turnover with **high accuracy**.
- Identified key features contributing to employee attrition.
- Provided insights for HR teams to improve retention strategies.

## Future Improvements
- Integrate deep learning models for improved predictions.
- Deploy as a web application for real-time analysis.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Developed by **Amirali Mohseni**
