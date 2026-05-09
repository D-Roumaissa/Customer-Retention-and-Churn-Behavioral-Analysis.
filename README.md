# Customer-Retention-and-Churn-Behavioral-Analysis-

## 🎯 Project Overview

This project is a high-end behavioral analytics tool designed to help Management and Client Service teams identify at-risk customers. By analyzing historical data from the **Telco Customer Churn dataset**, the AI identifies patterns—specifically comparing **Monthly** vs. **Yearly** membership types—to predict the likelihood of a customer canceling their subscription.

## 🚀 Key Features

* **Behavioral AI Engine:** Powered by a Random Forest Classifier to assess churn probability based on tenure, contract type, and monthly spend.
* **Executive Dashboard:** A professional, clean "FinTech" interface built with Gradio.
* **Strategic Visuals:**
* **Membership Portions (Donut Chart):** Visualizes the current distribution of contract types.
* **Risk Comparison (Bar Chart):** Directly compares the churn rate of monthly vs. yearly members.
* **Retention Curves (KDE Plot):** Shows the density of the customer lifecycle to identify "danger zones."


* **Financial Impact Analysis:** Provides automated management recommendations and estimates annual revenue at risk.

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`
* **Visuals:** `Matplotlib`, `Seaborn`
* **Front-End:** `Gradio`
* **Environment:** Google Colab / Jupyter Notebooks

## 📂 Dataset

The project utilizes the **WA_Fn-UseC_-Telco-Customer-Churn.csv** dataset. It includes customer metadata such as:

* **Contract Type:** Month-to-month, One year, Two year.
* **Tenure:** Number of months the customer has stayed with the company.
* **Monthly Charges:** The amount charged to the customer monthly.
* **Churn:** Whether the customer left within the last month.

## ⚙️ Installation & Usage

1. **Open Google Colab.**
2. **Copy and paste the three cells** provided in the project:
* *Cell 1:* Data loading and Graph generation.
* *Cell 2:* AI Model training.
* *Cell 3:* Launching the Gradio Dashboard.


3. **Run the cells.** A public or local URL will be generated to access the decorative front-end.

## 📈 Management Insights

Based on the behavioral analysis:

* **Monthly Subscribers:** Represent the highest revenue volatility.
* **Yearly Subscribers:** Form the "Stable Core" of the business with significantly lower attrition.
* **Actionable Strategy:** The model suggests converting high-risk monthly users to yearly contracts during their first 6 months of tenure to maximize retention.
<img width="862" height="568" alt="20260510_005725" src="https://github.com/user-attachments/assets/1fb49c7f-ebf7-4039-ae3b-f5b235b45c5b" />
