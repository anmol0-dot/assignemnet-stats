# 🧠 Decision Tree Classifier -- Pima Indian Diabetes Dataset

## 📌 Overview

This project demonstrates how to build a **Decision Tree Classifier**
using the **Pima Indian Diabetes Dataset** from Kaggle.\
It includes: - Loading and exploring the dataset\
- Feature selection\
- Train-test splitting\
- Building a decision tree using **Entropy** and **Gini Index**\
- Visualizing the decision tree\
- Manually computing **Entropy**, **Information Gain**, and **Gini
Index**

------------------------------------------------------------------------

## 📁 Dataset

You can download the dataset from Kaggle:\
**Pima Indians Diabetes Database**

Required file name:

    diabetes.csv

------------------------------------------------------------------------

## 🚀 Steps Performed

### ✔ 1. Import Libraries

NumPy, Pandas, Matplotlib, Scikit-learn

### ✔ 2. Load Dataset

    df = pd.read_csv("diabetes.csv")

### ✔ 3. Feature Selection

    X = df.drop("Outcome", axis=1)
    y = df["Outcome"]

### ✔ 4. Train-Test Split

    train_test_split(X, y, test_size=0.2)

### ✔ 5. Build Decision Trees

-   Criterion = **entropy**
-   Criterion = **gini**

### ✔ 6. Visualize the Tree

Using `plot_tree()`

### ✔ 7. Compute Entropy, Gini, Information Gain

Formulas included inside notebook.

------------------------------------------------------------------------

## 📊 Visualization Example

The notebook generates a plotted decision tree showing splitting at each
node.

------------------------------------------------------------------------

## 📦 Files Included

-   `DecisionTree_Diabetes.ipynb` -- Full working Jupyter Notebook\
-   `README.md` -- This documentation

------------------------------------------------------------------------

## 🏁 Conclusion

This project helps you understand: - How decision trees work\
- How criteria like entropy & gini affect splits\
- How to compute information gain manually

Feel free to modify, experiment, and upgrade the model! 🚀

