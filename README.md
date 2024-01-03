# Vehicle_Loan_Default_Prediction


🔹 **Aim of the Project**

Financial institutions face significant losses due to vehicle loan defaults, leading to increased rejection rates. This project aims to analyze a dataset with 41 attributes to determine factors affecting vehicle loan default ratios and create a predictive model.

🔹**Domain: Finance**

🔹**Flow of the Project:**

🔹**Data Inspection:**
Conducted preliminary data inspection to understand the structure of the data.

🔹**Data Collection:**

🔹**Data Cleaning and Preprocessing:**
Identified missing values, duplicates, and cleaned variable names.

🔹**Exploratory Data Analysis (EDA):**

**Statistical Description:**
Provided statistical description of the variables used in the dataset.

**Target Variable Analysis:**
Examined the distribution of the target variable (defaulters/non-defaulters) using a Count plot & found this is an Imbalanced dataset

**Categorical Variable Analysis:**
Studied target variable distribution across various categories (branch, state, manufacturer) and visualized it using bar charts.

**Employment Types:** 
Used pie charts to show the distribution of different Employment types such as Salaried and Self-employed and devise strategies to handle missing values. 

**Age Analysis:**
Investigated the relationship between age and loan defaulters by plotting the distribution of age w.r.t defaulters and non-defaulters.

**Proof of Identity:**
Determined the most common type of ID presented by customers as proof.

**Heatmap for Correlation**
Plotted a Heatmap to find the Correlation between the target variable and other variables used in the dataset.

**Primary and Secondary Account Details:**
Explored the relationship between primary and secondary account details and loan default probability.

**Outlier Detection:** 
Detected Outliers by plotting a Box plot of the quantitative data such as 'disbursed_amount', 'asset_cost', 'ltv','PERFORM_CNS_SCORE','age'.


🔹**Feature Engineering:**
•	Separating features and target variables.

•	Y as dependent variables

•	X as the independent variable

•	Since our dataset is imbalanced, tried to balance it using Under Sampling technique using SMOTE (Synthetic Minority Oversampling Technique)

🔹**Model Building:**
Training and Testing: 
•	splitting the dataframes into training and testing sets (x_train, x_test, y_train, and y_test)

•	Used various models such as Logistic Regression modeling, Random Forest, KNN to predict outcomes for test data.

🔹**Model Evaluation:**
•	Evaluated and validated results using the confusion matrix.

•	Presented the performance metrics such as accuracy, precision, recall, f1-score, and support and discussed the model's effectiveness.

🔹**Conclusion:**
From the observation, we can see that the **KNN model** performs better with an **accuracy score of 70.34%**.

🔹 **Building Dashboard:**
Visualized data using Tableau to enhance user exploration and understanding, aiding in informed business decision-making.

![Vehicle Loan Default Prediction](https://github.com/nidhidivecha/Vehicle_Loan_Default_Prediction/assets/54711762/36616258-5086-497d-9c4a-d6cf6ada3d68)

