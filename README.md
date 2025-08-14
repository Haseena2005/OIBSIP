TASK 1: Fraud Detection

Objective:

The objective of this project is to detect fraudulent transactions using historical transaction data. The model identifies suspicious transactions based on patterns and anomalies to help reduce financial losses.

Steps Performed:

1. **Data Loading & Exploration**

   * Imported dataset using **Pandas**.
   * Checked dataset shape, data types, and first few records.
   * Analyzed class distribution to understand the imbalance between fraudulent and non-fraudulent transactions.

2. **Data Preprocessing**

   * Handled missing values (if any).
   * Normalized numerical features for better model performance.

3. **Exploratory Data Analysis (EDA)**

   * Visualized transaction amount distribution.
   * Checked correlation between features using a heatmap.
   * Observed patterns in fraudulent vs. non-fraudulent transactions.

4. **Model Training**

   * Split data into **training** and **testing** sets.
   * Used classification algorithms such as **Logistic Regression** or **Random Forest**.
   * Applied techniques like **SMOTE** for handling class imbalance (if used).

5. **Evaluation**

   * Calculated **Accuracy, Precision, Recall, F1-Score**.
   * Generated a **Confusion Matrix** to visualize prediction performance.

Tools & Libraries Used:

* **Python**: Core programming language
* **Pandas**, **NumPy**: Data handling and preprocessing
* **Matplotlib**, **Seaborn**: Data visualization
* **Scikit-learn**: Model building and evaluation

Outcome:

* Built a model capable of detecting fraudulent transactions with high accuracy.
* Visual insights helped understand patterns that differentiate fraud from legitimate transactions.
* Can be applied in real-time monitoring systems for fraud prevention.

---

TASK 2: Wine Quality Prediction

Objective:

The aim of this project is to predict the quality of wine based on its physicochemical features using a classification model.

Steps Performed:

1. **Data Loading & Exploration**

   * Loaded wine quality dataset.
   * Checked data structure, feature types, and missing values.

2. **Data Preprocessing**

   * Normalized feature values using **StandardScaler**.
   * Converted wine quality scores into binary or multi-class labels.

3. **Exploratory Data Analysis (EDA)**

   * Visualized feature distributions.
   * Checked correlation between wine features and quality score.

4. **Model Training**

   * Split dataset into training and testing sets.
   * Applied classification algorithms like **Random Forest**, **Logistic Regression**, or **K-Nearest Neighbors**.

5. **Evaluation**

   * Measured performance using **Accuracy, Precision, Recall, and F1-score**.
   * Visualized Confusion Matrix for detailed predictions.

Tools & Libraries Used:

* **Python**: Programming language
* **Pandas**, **NumPy**: Data handling
* **Matplotlib**, **Seaborn**: Visualizations
* **Scikit-learn**: Model training & evaluation

 Outcome:

* Successfully classified wines into quality categories based on their chemical composition.
* Identified important features that influence wine quality the most.
* Can assist winemakers in maintaining and improving product quality.

---

TASK 3: Predicting House Prices with Linear Regression

Objective:

The goal is to predict house prices based on various features such as location, size, number of rooms, and other property attributes using regression models.

Steps Performed:

1. **Data Loading & Exploration**

   * Loaded housing dataset.
   * Checked for missing values and handled them appropriately.

2. **Data Preprocessing**

   * Converted categorical variables into numerical form using **One-Hot Encoding**.
   * Scaled numerical features using **StandardScaler**.

3. **Exploratory Data Analysis (EDA)**

   * Visualized price distribution and key feature relationships.
   * Checked correlation between features and house price.

4. **Model Training**

   * Split data into training and testing sets.
   * Used regression algorithms like **Linear Regression**, **Random Forest Regressor**, or **Gradient Boosting**.

5. **Evaluation**

   * Measured performance using **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² score**.
   * Plotted predicted vs. actual prices for model validation.

Tools & Libraries Used:

* **Python**: Main programming language
* **Pandas**, **NumPy**: Data processing
* **Matplotlib**, **Seaborn**: Data visualization
* **Scikit-learn**: Model building & evaluation

Outcome:

* Developed a regression model capable of accurately predicting house prices.
* Visualizations provided insight into key factors affecting property value.
* Can be applied in real estate platforms for pricing recommendations.


