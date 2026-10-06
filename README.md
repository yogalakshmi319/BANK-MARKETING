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

Categorical variables are converted into numeri
