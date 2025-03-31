# CODECRAFT_DS_03
# Decision Tree for Customer purchasing Behaviour 
Overview

This project utilizes a Decision Tree algorithm to analyze customer purchasing behavior. The model predicts whether a customer will make a purchase based on various factors such as age, income, browsing history, and previous purchases.

Features

Data Preprocessing: Handles missing values, encodes categorical variables, and scales numerical data.

Decision Tree Model: Implements a classification decision tree to predict purchasing behavior.

Visualization: Generates a graphical representation of the decision tree for better interpretability.

Performance Metrics: Evaluates the model using accuracy, precision, recall, and F1-score.

Dataset

The dataset includes customer attributes such as:

Age

Income

Browsing Duration

Number of Past Purchases

Product Category Interest

Purchase Decision (Yes/No)

Installation

To run this project, install the required dependencies using:

pip install pandas numpy scikit-learn matplotlib seaborn

Usage

Clone the repository:

git clone https://github.com/your-repo/decision-tree-purchasing-behavior.git

Navigate to the project directory:

cd decision-tree-purchasing-behavior

Run the script:

python decision_tree.py

Model Training

The dataset is split into training (80%) and testing (20%) sets.

A Decision Tree Classifier is trained on the data.

Hyperparameter tuning is done using GridSearchCV.

Evaluation Metrics

The model is assessed using:

Accuracy Score

Confusion Matrix

Precision, Recall, F1-score

Visualization

The decision tree structure is plotted using matplotlib and scikit-learn.

Feature importance is analyzed to understand key purchasing factors.

Future Improvements

Implementing Random Forest for better generalization.

Using Neural Networks to enhance predictive accuracy.

Exploring additional features like social media engagement.

Contributing

Feel free to contribute by opening an issue or submitting a pull request.

License

This project is licensed under the MIT License.
