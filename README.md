SUPPORT TICKET CLASSIFICATION & PRIORITISATION 

Project Overview:
Customer support teams receive a large number of tickets daily. Manually categorizing 
and prioritizing them is time-consuming and inefficient.

This project uses Machine Learning (NLP) to automatically:
- Classify support tickets into categories
- Assign priority levels (Critical / High / Medium / Low)

Objective:
Build an ML system that:
- Reads ticket text
- Predicts **category** (Billing, Technical Issue, etc.)
- Predicts **priority** (Critical, High, Medium, Low)

Tech Stack:
- Python
- Pandas
- Scikit-learn
- TF-IDF (Text Vectorization)
- Logistic Regression

 Workflow:
1. Data Loading
2. Text Preprocessing (cleaning text)
3. Feature Extraction using TF-IDF
4. Model Training using Logistic Regression
5. Model Evaluation
6. Prediction System

Model Results:

🔹 Accuracy
- Category Accuracy: 0.20
- Priority Accuracy: 0.26
🔹 Sample Predictions
Input: My payment failed and money got deducted
Category: Product inquiry Priority: Medium
Input: Unable to login to my account
 Category: Technical issue Priority: Medium
Input: I want to cancel my order
Category: Billing inquiry Priority: Critical
Input: App is not working properly
Category: Technical issue Priority: High
Input: Need refund for my purchase
 Category: Refund request Priority: Low

Model Analysis:

Model works correctly for classification and prioritization
Accuracy is moderate due to repetitive dataset
Many tickets have similar wording
Still demonstrates real-world ML pipeline

Project Structure:
support-ticket-classification
├── tickets.py
├── customer_support_tickets.csv
├── README.md

How to Run:
pip install pandas scikit-learn
python tickets.py

Conclusion:
This project demonstrates how Machine Learning can automate support ticket classification 
and prioritization in real-world systems.
