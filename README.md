# Heart-disease-prediction
The Heart Disease Prediction System utilizes multiple ML models (Logistic Regression, Decision Trees, Random Forest, SVM, KNN, XGBoost) to analyze patient data and predict heart disease risk with performance evaluation.Heart Disease Prediction System
Overview
The Heart Disease Prediction System is a machine learning-based project that predicts the likelihood of heart disease using patient health data. It utilizes multiple classification models, including Logistic Regression, Decision Trees, Random Forest, XGBoost, and K-Nearest Neighbors (KNN), to analyze medical parameters such as age, cholesterol levels, blood pressure, and heart rate. The system is trained, tested, and evaluated using various performance metrics like accuracy, precision, recall, and F1-score to identify the best model for prediction.

Features
✅ Data Collection & Preprocessing (handling missing values, feature scaling)
✅ Model Training with multiple ML algorithms
✅ Performance Evaluation using metrics like accuracy and confusion matrix
✅ Predictive System for individual heart disease risk assessment
✅ Data Visualization with Seaborn and Matplotlib

Tech Stack
Programming Language: Python
Libraries Used: NumPy, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn
Machine Learning Models: Logistic Regression, Decision Trees, Random Forest, XGBoost, KNN
Dataset: CSV-based heart disease dataset
Installation & Setup
Clone this repository:
bash
Copy code
git clone https://github.com/your-repo/heart-disease-prediction.git
cd heart-disease-prediction
Install dependencies:
bash
Copy code
pip install numpy pandas scikit-learn matplotlib seaborn xgboost
Run the script:
bash
Copy code
python heart_disease_prediction.py
Usage
The model will train on the dataset and display evaluation metrics.
To predict heart disease for a new patient, modify the input_data section in the script.
The system will output whether the person is at risk of heart disease.
Results & Evaluation
The trained models are evaluated on test data using accuracy, precision, recall, and F1-score.
The confusion matrix provides insights into false positives and false negatives.
The best-performing model can be selected for deployment.
Future Enhancements
🔹 Deploy as a web app using Flask/Django
🔹 Implement Deep Learning for better accuracy
🔹 Expand dataset for real-world generalization

Contributors
Your Name (Replace with your details)
License
This project is open-source under the MIT License.

