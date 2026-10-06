# 🏦 BANK MARKETING PREDICTION USING MACHINE LEARNING

**📌 Project Overview**

This project focuses on predicting whether a bank customer will subscribe to a term deposit using Machine Learning techniques.

The project uses the Bank Marketing dataset and applies data preprocessing, categorical encoding, feature selection, SMOTE, transformation, feature scaling, and different Machine Learning classification algorithms.

The models are evaluated using Accuracy, Precision, Recall, and F1-Score.

**🎯 Project Objective**

• To understand the Bank Marketing dataset.
• To perform data preprocessing.
• To convert categorical data into numerical form.
• To handle class imbalance using SMOTE.
• To select important features.
• To transform and scale the data.
• To train different Machine Learning classification models.
• To compare the performance of different models.
• To identify the best-performing model.

**❓ Problem Statement**

Banks conduct marketing campaigns to contact customers and promote term deposit products.

The objective of this project is to predict whether a customer will subscribe to a term deposit based on customer and campaign-related information.

**📊 Dataset**

Dataset Name: Bank Marketing Dataset

The dataset contains 45,211 customer records and 17 attributes.

**📝 Dataset Features**

• age – Age of the customer
• job – Type of job
• marital – Marital status
• education – Education level
• default – Whether the customer has credit in default
• balance – Average yearly balance
• housing – Whether the customer has a housing loan
• loan – Whether the customer has a personal loan
• contact – Contact communication type
• day – Last contact day
• month – Last contact month
• duration – Duration of the last contact
• campaign – Number of contacts performed during the campaign
• pdays – Number of days since the customer was last contacted
• previous – Number of contacts performed before this campaign
• poutcome – Outcome of the previous marketing campaign
• y – Whether the customer subscribed to a term deposit

**🎯 Target Variable**

The target variable is **y**.

• no – Customer did not subscribe
• yes – Customer subscribed

**📈 Target Distribution**

• no – 39,922
• yes – 5,289

**💻 Technologies Used**

• Python
• Jupyter Notebook
• Pandas
• NumPy
• Matplotlib
• Seaborn
• Scikit-learn
• Imbalanced-learn
• OpenPyXL

**📚 Libraries Used**

• Pandas – Data loading and data manipulation
• NumPy – Numerical operations
• Matplotlib – Data visualization
• Seaborn – Statistical visualization
• Scikit-learn – Machine Learning algorithms and preprocessing
• Imbalanced-learn – SMOTE for handling class imbalance
• OpenPyXL – Reading Excel files

**📂 Data Loading**

The dataset is stored as an Excel file.

The dataset is loaded using Pandas:

`data = pd.read_excel("bank-full.xlsx")`

**🔍 Data Exploration**

The dataset is explored using:

• First few records
• Dataset shape
• Column names
• Data types
• Target variable distribution
• Descriptive statistics
• Categorical and numerical features

**⚙️ Data Preprocessing**

The following preprocessing techniques are applied:

• Checking the dataset
• Handling categorical variables
• Encoding categorical data
• Feature transformation
• Handling class imbalance
• Feature selection
• Feature scaling

**🔤 Categorical Data Encoding**

Categorical variables are converted into numerical representations using encoding techniques so that they can be used by Machine Learning algorithms.

🔢 One-Hot Encoding

One-Hot Encoding is applied to categorical features to convert categorical values into separate numerical columns.

🎂 Age Transformation

The age feature is transformed into encoded features during the preprocessing stage.

The original age column is removed after transformation.

⚖️ Handling Class Imbalance

The target variable contains more no values than yes values.

To handle this class imbalance, SMOTE (Synthetic Minority Over-sampling Technique) is used.

SMOTE generates synthetic samples for the minority class so that the Machine Learning model can learn both classes more effectively.

🔎 Feature Selection

Feature selection is performed using SelectKBest with f_classif.

The top 25 important features are selected for model training.

🔄 Data Transformation

Yeo-Johnson transformation is applied using PowerTransformer.

This transformation helps improve the distribution of the features.

📏 Feature Scaling

StandardScaler is used to standardize the selected features.

🤖 Machine Learning Algorithms

The following classification algorithms are used:

1️⃣ Logistic Regression

Logistic Regression is a classification algorithm used to predict the probability of a binary outcome.

2️⃣ Decision Tree

Decision Tree uses a tree-like structure to make classification decisions based on feature values.

3️⃣ Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to produce better predictions.

4️⃣ AdaBoost

AdaBoost is an ensemble technique that combines multiple weak learners to create a stronger classifier.

5️⃣ Gradient Boosting

Gradient Boosting builds models sequentially, where each new model attempts to improve the errors made by previous models.

📊 Model Evaluation

The models are evaluated using:

• Accuracy
• Precision
• Recall
• F1-Score

📋 Model Performance

Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	0.88	0.52	0.09	0.15
Decision Tree	0.84	0.32	0.35	0.33
Random Forest	0.89	0.55	0.25	0.35
AdaBoost	0.89	0.56	0.21	0.31
Gradient Boosting	0.89	0.56	0.22	0.32

🏆 Best Performing Model

Based on the F1-Score, Random Forest provides the best performance among the tested models.

• Accuracy – 0.89
• Precision – 0.55
• Recall – 0.25
• F1-Score – 0.35

🔄 Project Workflow

Dataset → Data Loading → Data Exploration → Data Preprocessing → Categorical Encoding → SMOTE → Feature Selection → Yeo-Johnson Transformation → Feature Scaling → Model Training → Prediction → Evaluation → Model Comparison → Best Model Selection

📁 Project Folder Structure

Bank-Marketing-Prediction/
• bank marketing.ipynb
• bank-full.xlsx
• README.md

📦 Requirements

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn openpyxl jupyter

▶️ How to Run the Project

Install Python.
Install the required libraries.
Place bank marketing.ipynb and bank-full.xlsx in the same folder.
Open the notebook using Jupyter Notebook or VS Code.
Open bank marketing.ipynb.
Make sure the dataset loading code is:

data = pd.read_excel("bank-full.xlsx")

Run all the cells from beginning to end.
The notebook will perform preprocessing, model training, prediction, and evaluation.

📤 Expected Output

The project produces:

• Dataset exploration results
• Target variable distribution
• Preprocessed data
• Encoded features
• SMOTE-balanced data
• Selected features
• Transformed and scaled data
• Predictions from different Machine Learning models
• Accuracy
• Precision
• Recall
• F1-Score
• Model comparison
• Best-performing model

✅ Conclusion

This project demonstrates the use of Machine Learning for predicting customer subscription in a bank marketing campaign.

Different classification algorithms are trained and evaluated using Accuracy, Precision, Recall, and F1-Score.

Among the tested models, Random Forest achieved the highest F1-Score and performed comparatively better for this dataset.

🚀 Future Enhancement

The project can be further improved by:

• Testing additional Machine Learning algorithms.
• Performing hyperparameter tuning to improve model performance.
• Improving feature engineering and data preprocessing.
• Developing a simple user interface for customer prediction.
• Deploying the model as a web application.
