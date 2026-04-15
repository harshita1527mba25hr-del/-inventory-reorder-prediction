Inventory Reorder Prediction using Decision Tree
Project Overview
This project focuses on building a Machine Learning model to predict whether a product needs to be reordered based on inventory-related factors. The model uses a Decision Tree Classifier to analyze patterns in sales, stock levels, lead time, and demand trends.
The goal is to simulate a smart inventory management system that helps businesses make efficient restocking decisions.

 Objectives
Generate a synthetic dataset for inventory analysis
Understand feature relationships affecting stock decisions
Train a Decision Tree model for classification
Predict whether reorder is required or not
Interpret model output for real-world decision making

 Problem Statement
Businesses often struggle with:
Overstocking (wasting resources)
Understocking (losing sales)
This project solves the problem by predicting:
 "Should we reorder stock or not?"

 Dataset Description
The dataset is randomly generated and contains the following features:
Feature Name
Description
daily_sales
Number of units sold per day
stock_available
Current inventory level
lead_time
Days required to restock
demand_trend
Demand level (1 = Low, 2 = Medium, 3 = High)
reorder
Target variable (1 = Yes, 0 = No)


 Working Process
Step 1: Data Generation
Random dataset created using NumPy
Simulates real-world inventory conditions
Step 2: Target Logic
Reorder is triggered when:
Stock is less than required during lead time
OR demand is high and stock is low
Step 3: Model Training
Algorithm used: Decision Tree Classifier
Model learns decision rules from dataset
Step 4: Prediction
Sample input is given:
[daily_sales, stock_available, lead_time, demand_trend]


Output:
1 → Reorder Required
0 → Stock is Sufficient

 Sample Output
Prediction: 1  
Reorder Required


 Technologies & Tools Used
Python 🐍
Google Colab
Pandas
NumPy
Scikit-learn

 How to Run the Project
Open the notebook in Google Colab / Jupyter Notebook
Run all cells step by step
Observe dataset generation
Train the model
Check prediction output

 Key Learnings
Basics of supervised machine learning
Decision Tree working mechanism
Feature-based prediction
Real-world application of ML in inventory management

 Future Enhancements
Use real-world datasets
Apply advanced models (Random Forest, XGBoost)
Build a dashboard for visualization
Integrate with supply chain systems

 Conclusion
This project demonstrates how Machine Learning can help businesses optimize inventory decisions, reduce losses, and improve operational efficiency.

 Author
Harshita
