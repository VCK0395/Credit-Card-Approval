# 💳 Credit Card Application Approval Predictor

This project implements a complete Machine Learning workflow—from data loading and cleaning to model training and hyperparameter tuning—to predict credit card application approval. It uses a publicly available dataset of anonymous credit card applications.

---

## 💡 What It Does 

This Python script builds and evaluates a **Logistic Regression** model to classify whether a credit card application will be approved.

The process includes:

1.  **Exploratory Data Analysis (EDA):** Initial inspection of the dataset structure, statistics, and missing values.
2.  **Data Preprocessing:** Handling missing data through **mean** imputation for numerical features and **most frequent value** (mode) imputation for categorical features.
3.  **Feature Engineering:** Dropping irrelevant features, encoding categorical variables using **One-Hot Encoding** (`pd.get_dummies`), and scaling numerical features using **MinMaxScaler**.
4.  **Model Training and Evaluation:** Training a Logistic Regression classifier, evaluating its performance using **accuracy score** and a **confusion matrix**.
5.  **Hyperparameter Optimization:** Using **GridSearchCV** to find the optimal values for the regularization tolerance (`tol`) and maximum iterations (`max_iter`) to improve the model's performance.

---

## 🛠️ How to Use It 

### Prerequisites

To run this script, you need a Python environment with the following libraries installed:

* **Pandas**
* **NumPy**
* **Scikit-learn**

### Setup and Installation

1.  **Clone the Repository** (or save the code as a Python file, e.g., `cc_predictor.py`):
    ```bash
    git clone [your-repo-url]
    cd [your-repo-name]
    ```

2.  **Ensure Dataset is Present:**
