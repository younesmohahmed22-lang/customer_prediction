Customer Churn Prediction

📌 Project Overview

This project predicts whether a customer is likely to leave a telecommunications company using Machine Learning techniques.

The project compares multiple classification models and selects the best-performing model based on the F1-score. A Streamlit web application allows users to interact with the prediction system.

🎯 Project Objectives

- Analyze customer data to understand churn behavior.
- Preprocess customer data for machine learning.
- Train and evaluate multiple classification models.
- Select the best model based on F1-score.
- Build an interactive web application using Streamlit.

📊 Dataset

The project uses the Telco Customer Churn Dataset, which contains customer information such as:

- Customer demographics.
- Contract and payment information.
- Internet and phone services.
- Monthly and total charges.
- Customer churn status.

Dataset source: "Telco Customer Churn – Kaggle" (https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

🤖 Machine Learning Models

The project compares the following classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Models are evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC where applicable.

🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Joblib
- Streamlit

📁 Project Structure

customer-churn-prediction/
│
├── app.py
├── train.py
├── dataprocessing.py
├── requirements.txt
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
└── models/
    ├── churn_model.joblib
    ├── best_model_name.txt
    └── results.csv

⚙️ Installation and Setup

1. Clone the repository

git clone YOUR_GITHUB_REPOSITORY_URL
cd customer-churn-prediction

Replace "YOUR_GITHUB_REPOSITORY_URL" with your actual GitHub repository URL.

2. Install dependencies

pip install -r requirements.txt

3. Train the models

python train.py

This trains and evaluates the models, selects the best model based on F1-score, and saves the model and evaluation results.

4. Run the Streamlit application

streamlit run app.py

Open the local URL displayed in your terminal to use the application.

🚀 Deployment

The application can be deployed online using Streamlit Community Cloud.

1. Upload the project to GitHub.
2. Visit "Streamlit Community Cloud" (https://share.streamlit.io/).
3. Connect your GitHub account.
4. Select the repository and the "app.py" file.
5. Click Deploy.

📈 Results

The training script compares all supported models and selects the model with the highest F1-score.

The current training run selected Logistic Regression as the best model according to F1-score. Results may change when the dataset, preprocessing, or model parameters change.

👨‍💻 Author

Developed as a Machine Learning project to practice data preprocessing, classification, model evaluation, and deployment.

📄 License

This project is intended for educational and learning purposes.