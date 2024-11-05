Loan Eligibility Prediction Model

This project demonstrates a data-driven approach to predicting loan eligibility using machine learning. It provides an end-to-end solution, from data preprocessing to model evaluation, leveraging Python’s powerful data science libraries. Developed with support from [Future Inter], this project offers a comprehensive exploration of how machine learning can be used to make informed lending decisions.

📊 Project Overview
The goal of this project is to classify applicants as eligible or ineligible for a loan based on various attributes such as income, loan amount, credit history, and more. Through data analysis, we gain insights into the applicant demographics, identify trends, and build a model that helps in understanding key factors affecting loan eligibility.

🔑 Key Steps & Techniques
Data Cleaning & Preprocessing: Handled missing values, normalized skewed distributions, and converted categorical variables into numerical format for optimal model performance.
Exploratory Data Analysis (EDA): Visualized income distributions, credit history impact, and other trends with histograms, cross-tabulations, and box plots.
Modeling & Evaluation: Decision Tree Classifier: Trained an initial model, achieving an accuracy of 67%.
Naive Bayes Classifier: Improved accuracy to 82%, showcasing its effectiveness on this dataset.
Clustering with KMeans: Added KMeans clustering for segmentation, offering another layer of insights into applicant categories.

🛠 Tools and Libraries
Pandas and Numpy for data manipulation
Matplotlib for data visualization
Scikit-Learn for machine learning models (Decision Tree, Naive Bayes, KMeans)

🚀 How to Use
Clone the repository.
Ensure all dependencies in requirements.txt are installed.
Run the Jupyter notebooks to view data preprocessing, EDA, and model training.
Adjust parameters and explore different models to see how they perform on the dataset.

📂 Files Included
loan.csv: Dataset used for model training and analysis.
notebooks/: Contains Jupyter notebooks with all data analysis and modeling steps.

📈 Results
The Naive Bayes Classifier outperformed the Decision Tree, achieving an accuracy of 82%. This result highlights the importance of model selection in predicting loan eligibility effectively.
