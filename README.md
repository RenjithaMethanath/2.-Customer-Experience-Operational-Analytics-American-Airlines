# ✈️ American Airlines – Customer Satisfaction & Operational Efficiency Analysis

This project focuses on identifying service-level gaps and operational inefficiencies within **American Airlines** using **Power BI** for data analysis and **HubSpot CRM** for customer engagement. Through a combination of dashboard-driven insights and CRM workflows, the goal is to enhance customer satisfaction and reduce flight delays.

---

## 🔍 Project Objectives

- Analyze customer satisfaction and delay data to uncover patterns and pain points.
- Segment customers based on feedback for personalized outreach.
- Predict and simulate improvements in satisfaction and operational performance.
- Integrate insights into a CRM system to automate email campaigns and ticket creation.

---

## 🧩 Datasets Used

- **Customer Satisfaction Dataset**: [Kaggle Link](https://www.kaggle.com/datasets/johndddddd/customer-satisfaction)
- **Airline Delay Cause Dataset**: [Kaggle Link](https://www.kaggle.com/datasets/ryanjt/airline-delay-cause)
- Additional mock data (names & emails) generated using **[Mockaroo](https://mockaroo.com/)**.

---

## 📊 Power BI Dashboards

Three dashboard pages were created:

### 1. Customer Satisfaction Overview
- Satisfaction rate vs target (0.43 vs 0.60)
- Service-wise average ratings (WiFi, Food, Seat comfort, etc.)
- Class-wise and customer type dissatisfaction insights

### 2. Operational Efficiency
- Total delay KPI and trends
- Delay breakdown by type and carrier
- Forecasting of delay reduction

### 3. Service Improvement Plan
- Correlation of service factors with satisfaction/delay
- Required improvements to reach performance targets
- Projected KPIs after interventions

---

## 🧠 Key Features & Logic

- **DAX Measures**: Custom formulas for satisfaction rate, delay analysis, improvements, and projections.
- **Python Integration**: Correlation matrices computed using pandas in Power BI.
- **Segmentation**: Customers grouped by satisfaction score, class, and service ratings.

---

## 💼 HubSpot CRM Implementation

- Contacts imported with mock name/email + satisfaction details.
- Static Lists Created:
  - `WiFi_dissatisfaction`
  - `Food_drink_dissatisfaction`
  - `Dissatisfied_customers_list`
  - `Loyal_Satisfied_Business_customers`
- **Emails Sent**: Personalized apologies, discount coupons, appreciation tokens
- **Ticket Workflow**: Created for each dissatisfied contact to simulate support system

---

## 🚀 Tools & Technologies

- **Power BI** – Visualization, modeling, forecasting, DAX & Python
- **HubSpot CRM** – Email marketing, segmentation, support workflows
- **Mockaroo** – Generating names and email IDs for CRM contact creation
- **Python (pandas)** – Correlation computation inside Power BI

---

## 📎 Use Cases

✅ Airline performance benchmarking  
✅ Customer sentiment tracking  
✅ Operational improvement planning  
✅ CRM-driven service recovery and loyalty

---
![Model Output](https://github.com/RenjithaMethanath/2.-Customer-Experience-Operational-Analytics-American-Airlines/blob/main/Screenshot%202025-04-12%20185524.png)
![Model Output](https://github.com/RenjithaMethanath/2.-Customer-Experience-Operational-Analytics-American-Airlines/blob/main/Screenshot%202025-04-12%20185540.png)
![Model Output](https://github.com/RenjithaMethanath/2.-Customer-Experience-Operational-Analytics-American-Airlines/blob/main/Screenshot%202025-04-12%20185223.png)
