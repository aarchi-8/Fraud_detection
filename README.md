# Fraud_detection
A system that can classify if a transaction is fraudulent or not Using Machine Learning Models.


🧠 Overview:
This project focuses on identifying fraudulent financial transactions using machine learning algorithms. I used a structured transactions dataset and applied data preprocessing, feature analysis, and multiple classification models (like Random Forest, AdaBoost, and Logistic Regression) to build a fraud detection system with high accuracy and reliability.

The goal is to detect unusual or suspicious activities, like transactions with abnormal amounts or locations, and flag them as potentially fraudulent.

🧰 Tools & Libraries Used:
Python Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

ML Algorithms: Random Forest, Logistic Regression, Decision Tree, AdaBoost, Gradient Boosting, Naïve Bayes

🔄 End-to-End Project Workflow:
🔹 1. Data Preprocessing
Loaded a transaction dataset

Dropped irrelevant columns like names and IDs

Checked for missing values (none were found)

🔹 2. Exploratory Data Analysis (EDA)
Boxplots and Histograms to detect outliers and visualize feature distribution

Fraudulent transactions often appear as outliers with unusually high amounts or frequency

🔹 3. Encoding & Feature Scaling
Applied Label Encoding for categorical columns (e.g., transaction type, location)

Used StandardScaler to scale numerical features

🔹 4. Correlation Analysis
Used heatmaps to find relationships between features

"Is_Fraud" label showed low correlation with individual features, indicating complex fraud behavior

🔹 5. Model Training & Evaluation
Split dataset: 75% for training, 25% for testing

Trained several models:

Random Forest, Logistic Regression, AdaBoost, etc.

Evaluated using Accuracy, Precision, Recall

Best models achieved ~94.88% accuracy

🔹 6. Model Comparison
Used bar charts to visualize model performance

Emphasized the importance of precision and recall over just accuracy (to minimize false negatives)

