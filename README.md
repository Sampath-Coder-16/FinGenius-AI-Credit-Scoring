# 💳 FinGenius – GenAI Credit Scoring for Financial Inclusion

## 👨‍💻 Author
Sampath Kumar Midde  
Final Year CSE Student  

---

## 🚀 Project Overview

FinGenius is an AI-powered credit scoring system designed for people who do not have a formal credit history.

Traditional systems rely on:
- CIBIL score
- Salary slips
- Bank statements

But millions of users (street vendors, gig workers, rural users) don’t have these.

👉 FinGenius solves this by using:
- UPI transactions
- SMS transaction logs
- Utility payments

---

## 🎯 Problem Statement

Many individuals are excluded from financial services due to lack of credit history.

This leads to:
- Loan rejection
- High-interest informal borrowing
- Financial inequality

---

## 💡 Solution

FinGenius uses an **Agent-Based GenAI System**:

### 🔹 Agents:
1. Data Collection Agent  
2. Preprocessing Agent  
3. Feature Engineering Agent  
4. Credit Scoring Agent  
5. Explainability Agent  
6. Compliance Agent  

---

## 🧠 How It Works

1. User uploads transaction data (CSV)
2. System extracts financial behavior
3. ML model predicts credit score
4. GenAI explains the decision
5. Output shows:
   - Credit Score
   - Risk Level
   - Explanation

---
🏗️ System Architecture
📌 Overview

FinGenius follows a multi-agent AI architecture designed to process alternative financial data and generate an explainable credit score.

The system is divided into modular components (agents), each responsible for a specific task in the pipeline.

🔄 Architecture Flow
User Input (CSV / API / SMS)
        ↓
Data Collection Agent
        ↓
Preprocessing Agent
        ↓
Feature Engineering Agent
        ↓
Risk Analysis Agent
        ↓
Credit Scoring Agent (ML Model)
        ↓
Explainability Agent (GenAI + SHAP)
        ↓
Compliance & Audit Agent
        ↓
Frontend / API Output
🧠 Component Description
1. Data Collection Agent
Collects user financial data from:
UPI transactions
SMS transaction alerts
Digital wallet logs
Utility bills
Accepts CSV input (for prototype)
2. Preprocessing Agent
Cleans raw data
Handles missing values
Normalizes transaction formats
Converts unstructured SMS → structured data
3. Feature Engineering Agent

Extracts meaningful financial behavior:

Total debit / credit
Transaction frequency
Average transaction amount
Utility payment consistency
Failed transaction ratio
4. Risk Analysis Agent
Detects anomalies
Identifies risky behavior patterns
Filters invalid or suspicious data
5. Credit Scoring Agent
Uses ML models:
XGBoost / Random Forest
Predicts:
Credit Score (0–100)
Risk Level (Low / Medium / High)
6. Explainability Agent (GenAI Layer)
Uses:
SHAP (feature importance)
LLM (for natural explanation)

Example Output:

“User has stable income and pays bills on time, resulting in low risk.”

7. Compliance & Audit Agent
Stores:
Input data
Features
Predictions
Ensures:
Transparency
Fairness
Audit trace
8. Frontend / API Layer
Built using:
Streamlit / FastAPI
Displays:
Credit Score
Risk Level
Explanation
📊 Architecture Diagram 
<img width="576" height="684" alt="image" src="https://github.com/user-attachments/assets/e7a76a8e-732f-442b-8baa-2c722a9bd7ce" />


⚙️ Key Design Principles
Modular Agent-Based Design
Explainable AI (XAI)
Scalable FinTech Architecture
Real-world data adaptability
Compliance-ready system
