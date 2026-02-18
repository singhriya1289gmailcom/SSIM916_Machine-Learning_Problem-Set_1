# SSIM916_Machine-Learning_Problem-Set_1

Diabetes Prediction Analysis
Project Overview
This project investigates the predictive power of clinical diagnostic measurements in identifying the risk of Type 2 diabetes. Using the Pima Indians Diabetes dataset, I compare three distinct machine learning paradigms—Logistic Regression, Random Forests, and Stochastic Gradient Descent (SGD) to determine which approach offers the most reliable classification performance for healthcare data.

How to Reproduce These Findings
To replicate the results presented in the analysis, please follow these steps:

Clone the Repository: Download this repository to your local machine or open it directly in a cloud environment like Google Colab.

Dataset Acquisition: Ensure the diabetes.csv file (Pima Indians Diabetes Dataset) is located in the same root directory as the notebook file.

Environment Setup: This analysis requires a Python 3 environment with the following libraries installed:

pandas (for data manipulation)

scikit-learn (for model implementation, scaling, and evaluation)

Execute the Notebook: Run the cells in Problem set 1.ipynb sequentially. The notebook is structured to perform data loading, feature scaling using StandardScaler, model training, and performance evaluation (Accuracy and Classification Reports) automatically.

Expected Output: The final cell will generate a comparison table of accuracy scores and detailed classification reports for all three models, identifying Logistic Regression as the optimal model for this specific task.
