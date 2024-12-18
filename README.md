# Crime-rate_prediction
This repository provides a machine learning-based tool to predict and analyze crime trends using various classification models. The interface allows users to upload a dataset, preprocess data, train models, and visualize crime patterns.

# Features
Upload Dataset: Upload your crime dataset (CSV format) for analysis.
Data Preprocessing: Handle missing values and process date/time information.
# Model Training:
Logistic Classifier
Naive Bayes Classifier (NB)
Decision Tree Classifier (DT)
Random Forest Classifier (RF)
Model Comparison: Compare model performance.
# Visualization:
Bar charts for crime types, arrests, and monthly crime trends.
Detailed analysis of specific crime types like THEFT, BATTERY, NARCOTICS, and CRIMINAL DAMAGE.
# Technologies Used
Python Libraries:
pandas for data processing
matplotlib and seaborn for visualizations
scikit-learn for machine learning models
# How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/your-repo-name.git
cd your-repo-name
Install dependencies:
bash
Copy code
pip install pandas matplotlib seaborn scikit-learn
Run the GUI (if implemented in crime1.py):
bash
Copy code
python crime1.py
Load your dataset and interact through the interface.
# Example Dataset
The tool works with structured crime datasets. Ensure your CSV includes columns such as:

Primary_Type: Type of crime
Description: Detailed description
Date: Date of the crime
Arrest: Arrest status
# Visual Outputs
Crime Trends: Monthly analysis of reported crimes.
Crime Distribution: Visualize distribution across categories like theft, narcotics, etc.
Arrests Analysis: Compare arrest counts per crime type.

