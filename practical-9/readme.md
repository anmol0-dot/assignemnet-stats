Iris Dataset KNN Classification
📌 K-Nearest Neighbors (KNN) on Iris Dataset

This project applies the KNN classification algorithm on the Iris dataset, including full EDA, scaling, model training, K-value comparison, and visualization.

✅ Steps Completed
Step 1 — Exploratory Data Analysis (EDA)

head()

describe()

groupby()

Step 2 — Feature Scaling

Used StandardScaler to normalize feature values before applying KNN.

Step 3 — Train–Test Split + KNN Training

Trained KNN with an initial value of k=5.

Step 4 — Confusion Matrix & Accuracy Score

Generated predictions and evaluated model accuracy.

Step 5 — Classification Report

Viewed precision, recall, F1-score for each Iris class.

Step 6 — Error Rate vs K Comparison

Computed error rate for K values from 1 to 20.

Step 7 — Error vs K Plot

Plotted error rate to identify the trend and best K.

Step 8 — Selected Best K

Picked the K value with the lowest error rate.

Step 9 — Visualization of Predictions

Plotted test results using the first two scaled features.

📊 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn (KNN, scaling, train-test split, metrics)

🚀 How to Run
pip install numpy pandas matplotlib seaborn scikit-learn
python iris_knn.py

📎 Outputs Included

EDA summary tables

Confusion Matrix

Classification Report

Error Rate vs K plot

Final KNN decision boundary scatter plot
