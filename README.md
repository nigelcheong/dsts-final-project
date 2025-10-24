# ✈️ Flight Delay Prediction — Data Science Pipeline (On-Premises & On-Cloud)

## 📘 Overview
This repository implements a local and on cloud workflows to predict whether a flight will be **delayed due to weather conditions**.  
The project is based on the *Final Project: Data Science Pipeline on-premises and on the cloud* assessment, which required building, training, and deploying predictive models both **locally** and **in AWS SageMaker**.

The business goal is to improve a travel-booking website’s customer experience by alerting users to possible flight delays when booking flights to or from the busiest U.S. airports.

Two complete notebooks are provided:

- **On-Premises (Part A):** Local Jupyter-based workflow using `pandas`, `scikit-learn`, `matplotlib`, and `seaborn`.  
- **On-Cloud (Part B):** Scalable AWS SageMaker workflow using **XGBoost** and **Linear Learner** for training, deployment, and batch inference.

---

## 📂 Repository Structure
.<br>
├── onpremises.ipynb # Local pipeline (EDA, feature engineering, Logistic Regression)<br>
├── oncloud.ipynb # Cloud pipeline (SageMaker training, deployment, batch transform)<br>
├── dashboard/ # Visual outputs and dashboards<br>
│ └── Dashboard 1.png<br>
├── requirements.txt # Python dependencies<br>
└── README.md # Project documentation<br>

## ⚙️ Requirements & Installation
To set up the environment locally:

```bash
pip install -r requirements.txt