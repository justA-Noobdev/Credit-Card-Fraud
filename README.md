Credit Card Fraud Detection Models
==================================

This repository contains Credit Card Fraud Detection models implemented using scikit-learn and snapML libraries. The models are built using the DecisionTreeClassifier and Support Vector Machine (SVM) algorithms.

Dataset
-------

The dataset used for training and evaluation is a labeled dataset of credit card transactions, where each transaction is labeled as either fraudulent or legitimate. It consists of various features related to the transaction, such as the transaction amount, time, and other anonymized features. The dataset is preprocessed and split into training and testing sets.

Models
------

### Decision Tree Classifier

The Decision Tree Classifier is implemented using scikit-learn library. Decision trees are a popular choice for classification tasks as they provide interpretable rules for making predictions. The model learns a tree-like structure where each internal node represents a test on a specific feature, and each leaf node represents a class label.

### Support Vector Machine (SVM)

The Support Vector Machine (SVM) model is implemented using scikit-learn library. SVMs are powerful algorithms for binary classification tasks. They aim to find the optimal hyperplane that maximally separates the classes in the feature space. SVMs can handle both linear and non-linear classification problems by using different kernel functions.

### Comparison

#### Speed

In terms of speed, snapML library offers faster performance compared to scikit-learn. snapML utilizes advanced hardware acceleration techniques, such as parallel processing and optimized algorithms, to speed up the training and inference process. This can be particularly advantageous when dealing with large datasets or when real-time predictions are required.

#### Accuracy

Both scikit-learn and snapML provide accurate models for credit card fraud detection. However, the accuracy may vary depending on the specific dataset and the chosen hyperparameters. It is recommended to fine-tune the models and perform cross-validation to select the best hyperparameters for each algorithm.

#### Hinge Loss

Hinge loss is a loss function commonly used with Support Vector Machines (SVMs) for binary classification. It encourages the SVM model to correctly classify instances by maximizing the margin between the classes. The hinge loss function penalizes misclassifications more severely than other loss functions, such as the logistic loss. The scikit-learn library implements SVMs with hinge loss optimization.

Usage
-----

### Prerequisites

-   Python (3.x)
-   scikit-learn
-   snapML (optional, for snapML models)

### Instructions

1.  Clone the repository: `git clone https://github.com/justA-Noobdev/Credit-Card-Fraud.git`
2.  Install the required dependencies: `pip install pandas numpy scikit-learn matplotlib snapml`
3.  To run the Decision Tree Classifier and Support Vector Models open `CrediCardFraudDetection.ipynb`.


Results
-------

After running the models, the evaluation results will be displayed, including accuracy, precision, recall, and hinge loss. Additionally, the training and inference times will be recorded for comparison purposes.

License
-------

This project is licensed under the [MIT License](https://chat.openai.com/LICENSE).

Acknowledgments
---------------

The credit card fraud dataset used in this project is obtained from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). Special thanks to the contributors for providing this valuable dataset.
