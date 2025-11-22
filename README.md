# fruit-classifier-decision-tree

Predicting Citrus Fruits Using a Decision Tree

This project builds a machine learning model to classify citrus fruits (such as oranges and grapefruits) using the Decision Tree Classifier from scikit-learn. The workflow covers data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization.

📁 Project Structure
├── Predicting Citrus Fruits Using Decision Tree.ipynb
├── citrus.csv
└── README.md

📊 Dataset

The project uses citrus.csv, which contains physical characteristics of fruits such as:

Diameter

Weight

Color score

Label (orange / grapefruit)

🔍 Workflow

Importing Libraries
NumPy, Pandas, Matplotlib, Seaborn, scikit-learn.

Data Loading & Inspection
Checking shape, data types, missing values.

Exploratory Data Analysis

Feature distributions

Correlation matrix

Visual patterns using plots

Data Preprocessing

Splitting into train/test sets

Feature-target separation

Model Building

Training a DecisionTreeClassifier

Hyperparameter tuning (if included)

Model Evaluation

Accuracy score

Classification report

Confusion matrix visualization

📈 Results

The Decision Tree model successfully classifies citrus fruits based on physical measurements, demonstrating how simple models can perform well on structured datasets.

🛠️ Technologies Used

Python

NumPy / Pandas

Seaborn / Matplotlib

Scikit-learn

Jupyter Notebook
