# ChurnShield
# ChurnShield 🛡️ - Customer Churn Prediction & Auto-Intervention System

Welcome to **ChurnShield**, an end-to-end machine learning pipeline built to predict customer churn and trigger real-time intervention using Azure services. This project helps businesses retain their customers by leveraging intelligent churn prediction models, automated alerts, and scalable deployment.

## 🚀 Project Overview

**ChurnShield** is a machine learning system that:
- Predicts whether a customer is likely to churn (i.e., leave the service).
- Automatically triggers an intervention workflow to retain the customer.
- Deployed on Microsoft Azure using services like Azure Machine Learning, Logic Apps, and Bot Framework.

## 📊 Features

- 🔍 **ML Model for Churn Prediction** (using XGBoost)
- 🧠 **Real-time scoring** with Azure Machine Learning
- 🔔 **Auto-triggered workflows** using Logic Apps (email/SMS/Teams alerts)
- 🤖 **AI-powered bot integration** for personalized customer communication
- 💾 Model saved and deployed with **joblib + pickle**
- 🧾 Easy retraining support with new data

## ⚙️ Tech Stack

| Layer            | Tools / Services                      |
|------------------|----------------------------------------|
| Machine Learning | Python, Pandas, Scikit-learn, XGBoost  |
| Deployment       | Azure Machine Learning Studio, Compute |
| Automation       | Azure Logic Apps, Azure Functions      |
| Communication    | Azure Bot Service, Power Automate      |
| Storage          | Azure Blob Storage / Pickle Model      |

## 📂 Project Structure






## 🧪 How It Works

1. Upload historical customer data.
2. Train the model to classify churn (`Yes` or `No`).
3. Save model as `.pkl` using `joblib`.
4. Deploy the model to Azure ML.
5. Set up Logic App to listen for churn predictions.
6. Automatically send email/alert or activate bot when high churn risk is detected.

## 🧠 Sample Use Case

> A telecom company uses this system to detect which customers are likely to leave, and instantly sends them a discount offer or personalized support via bot or email — increasing retention and customer satisfaction.

## 💡 Future Enhancements

- Add Power BI dashboards for churn analytics
- Multi-channel communication (WhatsApp, SMS)
- Feedback loop to improve model over time

## 👤 Author

**Rakesh Bhagavan Vajrapu**  
Email: rakeshrb1411@gmail.com  
Connect with me on [LinkedIn](https://www.linkedin.com/)  