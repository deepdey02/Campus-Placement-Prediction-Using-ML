# Campus-Placement-Prediction-Using-ML
This project predicts whether a student will get placed during campus recruitment based on their academic and personal profiles.

 Project Workflow
 
Data Exploration & Cleaning
Explored placement dataset (Placement.csv)
Handled null values, removed unnecessary columns
Generated summary statistics and visualizations

Data Preprocessing

Encoded categorical features (board, stream, specialization, work experience, etc.)
Split dataset into training (80%) and testing (20%)
Model Training & Evaluation

Implemented multiple ML models:

Logistic Regression
Support Vector Machine (SVC)
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Gradient Boosting

Evaluated models using accuracy score

Compared model performances visually with bar plots

Deployment Preparation

Saved the best-performing model using Joblib
Built a simple Tkinter GUI for user-friendly predictions

 Results

Multiple models were tested, and their accuracy scores were compared.

Logistic Regression and Random Forest showed strong results for prediction.

 Tech Stack

Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
Model Persistence: Joblib
GUI: Tkinter
