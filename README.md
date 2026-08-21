# Geldium – Credit Delinquency Analytics & Collections Strategy

**Author: Himanshu Gupta**  
**Project Type: Data Analytics / Predictive Analytics**  
**Focus: Credit Risk, Delinquency Prediction & Responsible AI**

**Virtual Experience Provider: Forage**  
**Program: Tata Group – GenAI Powered Data Analytics / GenAI Virtual Experience**

---

## 🏢 Virtual Experience Context

This project was completed as part of a **Forage virtual experience with Tata Group**, focused on applying **Generative AI and data analytics concepts** to a business problem involving credit delinquency and collections.

The project work covers EDA, missing-data handling, predictive modeling, business recommendations and responsible/agentic AI considerations within the Geldium case study.

## 📌 Project Overview

This project analyzes customer credit and repayment data for **Geldium** to identify factors associated with credit delinquency and translate those insights into a practical collections strategy.

The project covers the complete analytical workflow:

- Exploratory Data Analysis (EDA)
- Data quality and missing-value analysis
- Missing-data imputation concepts
- Predictive model planning
- Logistic Regression for delinquency prediction
- Model evaluation metrics
- Business recommendations for collections
- Responsible and ethical AI considerations
- Agentic AI concepts for collections automation

The main objective is to understand **which customer characteristics and payment behaviors are associated with higher delinquency risk** and how those insights can support timely, fair and responsible customer outreach.

---

## 👨‍💻 About the Author

**Himanshu Gupta**

BCA Graduate | Aspiring Data Analyst

### Technical Interests

- Data Analytics
- SQL
- Python
- Excel
- Power BI
- Exploratory Data Analysis
- Machine Learning
- Business Intelligence
- Predictive Analytics

---

## 📊 Dataset

The project uses a customer-level delinquency dataset containing **500 records** with numerical and categorical variables relevant to credit-risk analysis.

### Key Variables

- Age
- Income
- Credit Score
- Credit Utilization
- Missed Payments
- Delinquent Account
- Loan Balance
- Debt-to-Income Ratio
- Employment Status
- Account Tenure
- Credit Card Type
- Location
- Six-month payment-status information

The project materials identify missing values in important financial fields, making data-quality assessment and imputation an important part of the analysis.

---

## 🔍 Exploratory Data Analysis

The EDA focuses on:

1. Understanding the structure and quality of the dataset
2. Identifying missing values
3. Examining important credit-risk indicators
4. Finding relationships between customer characteristics and delinquency
5. Identifying unusual or potentially problematic records
6. Preparing the dataset for predictive modeling

The supplied EDA material highlights **credit utilization, missed payments and debt-to-income ratio** as important risk indicators.

---

## 🧹 Missing Data & Imputation

Missing data is addressed as an important data-quality problem.

The project includes an imputation guide covering:

- Mean imputation
- Median imputation
- Mode imputation

The guide explains that mean can be useful when data is reasonably balanced, median is preferable when outliers may distort the average, and mode can be useful when one categorical value is particularly common.

---

## 🤖 Predictive Modeling

The predictive-model plan uses **Logistic Regression** to estimate the likelihood of a customer becoming delinquent.

### Target Variable

`Delinquent_Account`

### Candidate Features

```text
Credit_Utilization
Missed_Payments
Income
Debt_to_Income_Ratio
Account_Tenure
```

### Model Workflow

```text
Load Dataset
      ↓
Data Preparation
      ↓
Select Features & Target
      ↓
Train/Test Split
      ↓
Logistic Regression
      ↓
Generate Predictions
      ↓
Evaluate Model
```

Logistic Regression was selected because it is interpretable and suitable for binary classification, which is particularly useful when model decisions need to be explained to business stakeholders.

---

## 📈 Model Evaluation

The project considers the following evaluation metrics:

| Metric | Purpose |
|---|---|
| Accuracy | Measures overall correct predictions |
| Precision | Measures how many predicted positives are actually positive |
| Recall | Measures how many actual positive cases are identified |
| F1 Score | Balances precision and recall |
| AUC | Measures the model's ability to distinguish between classes |

For credit-risk use cases, **precision and recall are especially important** because both unnecessary interventions and missed high-risk customers can have business and customer impact.

---

## 💡 Key Business Insights

The project materials identify several important delinquency-risk patterns:

- Customers with **high credit utilization** show higher delinquency risk.
- Customers with **multiple missed payments** are more likely to become delinquent.
- Higher **debt-to-income ratios** are associated with increased risk.
- Some customers show unusual combinations such as high income with low credit scores and may require further investigation.

These insights can help a Collections team prioritize early and supportive outreach.

---

## 🎯 Collections Recommendation

One proposed strategy focuses on customers under 30 with two or more missed payments.

A **6-week pilot outreach campaign** can be used to provide proactive communication, payment-plan options or financial-support information before accounts become seriously delinquent.

The recommendation follows a SMART framework:

- **Specific:** Focus on a clearly defined high-risk segment
- **Measurable:** Track changes in delinquency
- **Actionable:** Use existing communication channels
- **Relevant:** Supports credit-risk reduction and customer outcomes
- **Time-bound:** Evaluate the strategy during a defined pilot period

---

## 🤝 Responsible AI

Because the project relates to financial behavior, responsible AI is an important component.

Key considerations include:

- Fairness
- Bias detection
- Explainability
- Transparency
- Data privacy
- Human oversight
- Responsible customer treatment

The project emphasizes using AI to support **early and supportive interventions rather than purely punitive actions**.

---

## 🧠 Agentic AI Concept

The project also explores how Agentic AI could support collections operations.

A potential workflow is:

```text
Customer Data
     ↓
Risk Assessment
     ↓
Business Rules + Model Prediction
     ↓
Risk Level
     ↓
Recommended Action
     ↓
Customer Outreach
     ↓
Human Review for Critical Decisions
     ↓
Outcome Monitoring & Learning
```

Examples of automated actions may include payment reminders, while sensitive actions such as personalized hardship plans should involve appropriate human oversight.

---

## 🖼️ Project Evidence / Screenshots

The repository includes selected screenshots from the project deliverables so visitors can quickly see the work covered in each stage.

### Task 1 – Exploratory Data Analysis & Imputation

**EDA Summary**

![Task 1 EDA](screenshots/task-1/Task_1_EDA_Summary.png)

**Imputation Guide**

![Task 1 Imputation](screenshots/task-1/Task_1_Imputation_Guide.png)

### Task 2 – Predictive Model Plan

![Task 2 Predictive Model](screenshots/task-2/Task_2_Predictive_Model.png)

### Task 3 – Business Summary & Collections Strategy

![Task 3 Business Summary](screenshots/task-3/Task_3_Business_Summary.png)

### GenAI / Agentic AI Presentation

A selected presentation slide highlights the role of Agentic AI and the balance between automated actions and human oversight.

![Role of Agentic AI](screenshots/presentation/Presentation_Slide_3_Agentic_AI.png)

> **Note:** These images are project evidence from the supplied assignment materials. The presentation file included in this repository is a template, so the selected presentation image is kept as supporting project material rather than represented as a completed original presentation.

## 📁 Repository Structure

```text
Geldium-Credit-Delinquency-Analytics/
│
├── data/
│   └── Delinquency_prediction_dataset.xlsx
│
├── docs/
│   ├── EDA_Summary_Report.docx
│   ├── Predictive_Model_Plan.docx
│   ├── Business_Summary_Report.docx
│   ├── Imputation_Guide.docx
│   └── Data_Analytics_Glossary.docx
│
├── presentation/
│   └── Presentation_Template.pptx
│
├── screenshots/
│   ├── task-1/
│   │   ├── Task_1_EDA_Summary.png
│   │   └── Task_1_Imputation_Guide.png
│   ├── task-2/
│   │   └── Task_2_Predictive_Model.png
│   ├── task-3/
│   │   └── Task_3_Business_Summary.png
│   └── presentation/
│       └── Presentation_Slide_3_Agentic_AI.png
│
├── README.md
└── .gitignore
```

---

## 🛠️ Skills Demonstrated

**Data Analytics**
- Exploratory Data Analysis
- Data Cleaning
- Missing Data Analysis
- Data Imputation
- Risk Analysis
- Business Insights

**Machine Learning**
- Logistic Regression
- Binary Classification
- Model Evaluation
- Precision & Recall
- F1 Score
- AUC

**Business & AI**
- Predictive Analytics
- Collections Strategy
- Responsible AI
- Explainable AI
- Agentic AI Concepts
- Data Storytelling

---

## 📚 Project Deliverables

This repository contains the project dataset and supporting project documents covering EDA, predictive modeling, business recommendations, imputation and presentation material.

---

## ⚠️ Project Note

Some documents included in this repository are based on the **provided assignment templates/example-answer materials**. The repository is organized for project documentation and portfolio presentation.

Where required, the example findings should be replaced with independently generated analysis and model results before presenting them as original experimental results.

---

## 👤 Author

**Himanshu Gupta**

**Aspiring Data Analyst | BCA Graduate**

Interested in transforming data into meaningful business insights using **SQL, Python, Excel, Power BI and Analytics**.

---

### ⭐ If you find this project useful, consider giving the repository a star!
