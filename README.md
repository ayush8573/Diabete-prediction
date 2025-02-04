This project focuses on predicting diabetes using machine learning techniques. It utilizes patient health data and applies classification algorithms to determine the likelihood of diabetes.

📂 Dataset
The dataset contains medical information such as:

Glucose Level
Blood Pressure
Insulin Level
BMI (Body Mass Index)
Age
Pregnancy Count (for females)
Diabetes Pedigree Function
🛠 Technologies Used
Python
Pandas & NumPy – Data manipulation and preprocessing
Matplotlib & Seaborn – Data visualization
Scikit-Learn – Machine learning models (SVM, Random Forest, XGBoost, etc.)
XGBoost – Boosting technique for better prediction accuracy
🔍 Data Preprocessing
Handling missing values
Feature scaling using StandardScaler()
Splitting data into training and testing sets
📊 Model Training
Multiple machine learning models were trained and evaluated:

Support Vector Machine (SVM)
Decision Tree
Random Forest
XGBoost
🎯 Evaluation Metrics
The models were evaluated based on:

Accuracy
Precision
Recall
F1-score
ROC-AUC Score
🚀 How to Run
Clone the repository:
bash
Copy
Edit
git clone https://github.com/your-username/diabetes-prediction.git
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the script:
bash
Copy
Edit
python diabetes_prediction.py
📌 Results & Insights
XGBoost achieved the highest accuracy.
Feature importance analysis revealed that Glucose and BMI were key indicators of diabetes.
