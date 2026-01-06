🎓 Student Success Predictor
📌 Project Overview
The Student Success Predictor is a machine learning project that predicts whether a student will Pass or Fail based on academic and lifestyle factors. The project follows a complete ML pipeline including data loading, preprocessing, feature scaling, model training, evaluation, and user-based prediction.

📂 Dataset
File name: student_sucess_dataset.csv
The dataset contains information related to student performance and habits.
Key Columns Used
StudyHours
Attendance
PassScore
SleepHours
Internet (categorical)
Passed (target variable)

🔍 Step 1: Data Loading & Understanding
Loaded dataset using Pandas
Displayed:
First 5 rows
Dataset shape (rows & columns)
Dataset information
Summary statistics
Missing values per column

🧹 Step 2: Data Preprocessing
Checked for missing values
Converted categorical columns into numerical form using Label Encoding
Internet → Yes = 1, No = 0
Passed → Pass = 1, Fail = 0
Verified updated data types after encoding

⚖️ Step 3: Feature Scaling
Selected important numerical features:
StudyHours
Attendance
PassScore
SleepHours
Applied StandardScaler to normalize feature values
Prepared:
Features (X)
Target variable (y)

🤖 Step 4: Model Training
Split data into training and testing sets (80% train, 20% test)
Used Logistic Regression for classification
Trained the model on scaled data

📊 Step 5: Model Evaluation
Generated:
Classification Report (Precision, Recall, F1-score)
Confusion Matrix
Visualized confusion matrix using Seaborn Heatmap

🧪 Step 6: User Input Prediction
Took user input from the console:
Study Hours
Attendance
Pass Score
Sleep Hours
Scaled user input
Predicted result as:
Pass
Fail
🛠️ Technologies Used
Python
Pandas & NumPy
Scikit-learn
Matplotlib

Seaborn

🎯 Project Outcome

This project demonstrates how machine learning can be used to analyze student data and predict academic success, making it useful for educational analysis and learning ML fundamentals.
