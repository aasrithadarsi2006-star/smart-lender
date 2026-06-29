# Smart Lender – Loan Eligibility Prediction System

## 📖 Overview

Smart Lender is a Machine Learning-powered web application developed using **Python** and **Flask** to predict the loan eligibility of applicants. It helps banks and financial institutions make faster and more accurate loan approval decisions by analyzing applicant information.

The system uses multiple classification algorithms, including **Decision Tree**, **Random Forest**, **K-Nearest Neighbors (KNN)**, and **XGBoost**, to predict whether a loan should be approved. The best-performing model is deployed through a user-friendly Flask web application.

---

## 🎯 Objectives

- Predict loan eligibility using Machine Learning.
- Compare multiple classification algorithms.
- Build an interactive Flask web application.
- Deploy the best-performing model for real-time predictions.

---

## ✨ Features

- Loan Eligibility Prediction
- User-Friendly Web Interface
- Real-Time Prediction Results
- Data Visualization and Analysis
- Multiple Machine Learning Models
- Best Model Selection and Deployment

---

## 🛠️ Technologies Used

- Python
- Flask
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 📂 Dataset

The project uses a Loan Eligibility dataset containing the following attributes:

- Gender
- Marital Status
- Education
- Employment Status
- Applicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

---

## 🚀 Project Workflow

### Phase 1: Environment Setup

- Install Python libraries
- Configure the development environment

### Phase 2: Dataset Collection & Understanding

- Load the loan eligibility dataset
- Analyze applicant information
- Understand relationships between features and loan approval

### Phase 3: Data Visualization & Analysis

Perform Exploratory Data Analysis (EDA) using:

- Count Plots
- Distribution Plots
- Bar Charts

### Phase 4: Data Preprocessing

- Handle missing values
- Fill numerical values using Mean
- Fill categorical values using Mode
- Encode categorical variables into numerical values

### Phase 5: Machine Learning Model Building

The following models are trained and evaluated:

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

The best-performing model is selected for deployment.

### Phase 6: Flask Web Application

The application contains:

- Home Page
- Loan Eligibility Prediction Interface
- User Input Form
- Prediction Result Page

---

## 📁 Project Structure

```text
Smart-Lender/
│
├── dataset/
├── models/
├── static/
├── templates/
├── app.py
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run the Project

### Step 1

Clone the repository.

```bash
git clone <repository-link>
```

### Step 2

Install the required libraries.

```bash
pip install -r requirements.txt
```

### Step 3

Run the Flask application.

```bash
python app.py
```

### Step 4

Open your browser and visit:

```text
http://127.0.0.1:5000/
```

---

## 📊 Expected Outcome

- Accurate loan eligibility prediction
- Comparison of Machine Learning models
- Interactive Flask-based web application
- Practical knowledge of Machine Learning and Flask development

---

## 📈 Future Enhancements

- Improve prediction accuracy
- Deploy the application on IBM Cloud
- Add user authentication
- Connect with a database
- Enhance the user interface

---

## 👨‍💻 Author

**Darsi Venkata Sai Lakshmi Aasritha**

B.Tech Student

---

## 📄 License

This project is developed for educational and internship purposes only.

---

## ⭐ Acknowledgement

This project was developed as part of the **Smart Bridge / APSCHE Internship Program** to gain practical experience in Machine Learning, Data Analysis, and Flask Web Development.
