<img width="1890" height="903" alt="image" src="https://github.com/user-attachments/assets/b6f00c8b-47e3-4be2-a12c-33011f140f58" />🚀 Next-Generation Diabetes Prediction using Explainable AI (XAI)

A Machine Learning + XAI Powered Healthcare Prediction System

📝 Project Overview

This project focuses on building a next-generation diabetes prediction system using Machine Learning integrated with Explainable AI (XAI) techniques. Traditional ML models are accurate but often behave like “black boxes.” This project solves that issue by offering transparent, interpretable, and trustworthy predictions using SHAP and LIME.

Users can input clinical parameters through an interactive Flask web interface, and the system instantly predicts diabetes risk along with clear feature-level explanations.

🎯 Key Features

🔍 Accurate ML Model trained using Logistic Regression, Random Forest, SVM, and Gradient Boosting

🧠 XAI Integration using SHAP and LIME

📊 Feature Importance Visualization

🖥️ Flask-based Web Interface (index.html)

📁 Model Exported as .joblib & .pkl

📈 Exploratory Data Analysis (EDA) notebook included

🔐 User-friendly, secure, and easy to deploy

📂 Project Structure
major project 2 clg/
│── app.py
│── diabetes.csv
│── best_model.joblib
│── diabetes_model.pkl
│── Dibetes_Prediction_Project.ipynb
│── templates/
│     └── index.html
│── Project Overview.pdf
│── Project and Code Info.pdf
│── Explainable_Artificial_Intelligence_XAI_for_the_Pr.pdf

🧰 Tech Stack Used

Python 3.12

Flask (Web App)

Pandas, NumPy (Data Processing)

Scikit-learn (Machine Learning Models)

Matplotlib / Seaborn (Visualizations)

SHAP / LIME (Explainable AI)

Joblib / Pickle (Model Serialization)

HTML, CSS (Frontend UI)

⚙️ How to Run the Project
1. Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

2. Install required libraries
pip install -r requirements.txt

3. Run the Flask App
python app.py

4. Open the app in browser
http://127.0.0.1:5000

📈 Model Workflow

Dataset Loading (diabetes.csv)

Data Cleaning & Preprocessing

Feature Engineering

Model Training (multiple algorithms)

Best Model Selection

Model Export (.joblib and .pkl)

XAI Analysis (SHAP & LIME)

Web Deployment using Flask

🧠 Explainable AI (XAI) Integration

The project explains predictions using:

SHAP Values → Global & Local Explanation

Force Plots → Individual patient insight

Feature Importance Plots

LIME Local Explanations

This makes the system reliable for doctors, researchers, and patients.

Web UI : <img width="1890" height="903" alt="image" src="https://github.com/user-attachments/assets/4bb35828-64f7-4f5e-99c0-894f90a3fdea" />

🚀 Future Enhancements

Add Deep Learning Models

Deploy on AWS / Render

Add user authentication

Add real-time patient dashboard

Mobile-friendly version

👨‍💻 Author

Sarthak Kumar
B.Tech CSIT | AI & ML Enthusiast
