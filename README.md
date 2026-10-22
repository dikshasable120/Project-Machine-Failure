# Project-Machine-Failure
# ⚙️ Machine Failure Prediction Project

## 🌐 Live Deployment

🚀 **Try the live application:** [Machine Failure Prediction – Streamlit App](https://project-machine-failure-hsqgiuh8x8c2vhlftgx3nf.streamlit.app/)

## 📌 Project Overview

The **Machine Failure Prediction Project** is a Machine Learning application designed to predict potential machine failures based on operational parameters and sensor data.

The project uses historical machine data to identify patterns associated with equipment failure. It demonstrates an end-to-end Machine Learning workflow, from data gathering and exploratory data analysis to model development and deployment using Streamlit.

## 🎯 Project Objectives

- Analyze machine operational and sensor data.
- Identify patterns associated with machine failures.
- Perform data cleaning and preprocessing.
- Build and evaluate Machine Learning classification models.
- Develop an interactive prediction application.
- Deploy the trained model for online access.

## 🔄 End-to-End Project Workflow

The project follows these steps, from raw data to a deployed Machine Learning application.

1. **Data Gathering** – Collect the machine dataset containing operational parameters, sensor measurements, and failure-related information.
2. **Data Understanding** – Examine dataset dimensions, column names, data types, target variables, and feature descriptions.
3. **Exploratory Data Analysis (EDA)** – Analyze feature distributions, identify patterns, explore relationships, and investigate failure rates using statistical summaries and visualizations.
4. **Data Cleaning** – Check for missing values, duplicate records, inconsistent entries, and potential data quality issues.
5. **Data Preprocessing** – Handle missing values where necessary, encode categorical variables, and prepare features for model training.
6. **Feature Selection** – Identify relevant machine parameters that may help predict failures.
7. **Train-Test Split** – Divide the dataset into training and testing sets to evaluate the model on unseen data.
8. **Model Building** – Train suitable supervised Machine Learning classification algorithms to predict machine failure.
9. **Model Evaluation** – Evaluate model performance using suitable metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
10. **Model Selection** – Select the most suitable model based on evaluation results, with particular attention to detecting actual failures.
11. **Model Saving** – Save the trained model and any required preprocessing objects for future predictions.
12. **Streamlit Application Development** – Create an interactive interface that accepts machine operational inputs and displays prediction results.
13. **Model Integration** – Connect the saved model and preprocessing components to the Streamlit application.
14. **Application Testing** – Test input handling, preprocessing consistency, prediction outputs, and application behavior.
15. **Model Deployment** – Deploy the application using Streamlit Community Cloud to make the prediction system accessible online.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Web Application Framework:** Streamlit
- **Model Serialization:** Pickle or Joblib, if used
- **Version Control:** Git and GitHub
- **Deployment Platform:** Streamlit Community Cloud

## ✨ Key Features

- Interactive interface for entering machine operational parameters.
- Machine Learning-based failure prediction.
- User-friendly prediction results.
- Data-driven analysis of machine failure patterns.
- Web-based access through a deployed Streamlit application.

## 🧠 Machine Learning Approach

This project uses **Supervised Machine Learning — Classification** to learn patterns from historical machine data.

- **Input:** Machine operational parameters and relevant sensor measurements.
- **Output:** Predicted failure status based on the target labels used in the dataset.
- **Goal:** Help identify potential machine failures and support proactive maintenance planning.

*Note: Predictions are estimates and should be validated before making maintenance or operational decisions.*

## 🚀 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project Folder

```bash
cd <your-project-folder>
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit Application

```bash
streamlit run app.py
```

## 📈 Learning Outcomes

- Understanding the end-to-end Machine Learning lifecycle.
- Performing data cleaning, preprocessing, and exploratory data analysis.
- Building and evaluating classification models.
- Understanding the importance of failure detection and recall.
- Integrating a trained model into a Streamlit application.
- Deploying a Machine Learning application to the cloud.

## 🌐 Live Application

👉 **[Click here to try the Machine Failure Prediction App](https://project-machine-failure-hsqgiuh8x8c2vhlftgx3nf.streamlit.app/)**

## 👩‍💻 Author

**Diksha Sable**

Aspiring Data Analyst | Machine Learning Enthusiast

