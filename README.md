# M505D-Intro-to-AI-and-Machine-Learning

Project Goal
This project develops a machine learning pipeline to predict whether a first-time e-commerce customer will make a repeat purchase. The goal is to identify high-potential repeat customers so the business can focus its marketing efforts, optimize spending, and increase customer lifetime value.

⚙ Workflow & Methodology
Data Cleaning: Loaded raw transactional data and handled missing customer_id values, converted data types, and removed return transactions.

Feature Engineering: Transformed the transactional data into a customer-level feature set. Key engineered features include TotalSpend, TransactionCount, DaysAsCustomer, and the target variable is_repeat.

Preprocessing & Balancing: Handled outliers by capping them at the 99th percentile, scaled numerical features, and one-hot encoded categorical features. Addressed a severe class imbalance in the training data using SMOTE.

Modeling: Trained and evaluated two models:

Random Forest Classifier (tuned with GridSearchCV)

Keras Neural Network (a simple MLP)

Setup & Technologies
Tech Stack: Python, pandas, scikit-learn, imbalanced-learn, TensorFlow (Keras).

To Run: Clone the repository, install dependencies from requirements.txt, and run the primary analysis notebook.
