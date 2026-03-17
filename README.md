# 📊 Customer Churn & Revenue Assurance Analysis

## **Project Background**
This project analyzes customer retention within the telecommunications industry to identify the primary drivers of churn. The objective is to transform raw subscriber data into actionable business strategies to mitigate **Revenue Leakage** and optimize **Monthly Recurring Revenue (MRR)**.

Insights and recommendations are provided on the following key areas:
* **Contractual Risk Analysis:** Evaluation of how contract types impact revenue stability.
* **Service Correlation:** Assessment of support services (e.g., Tech Support) on customer loyalty.
* **Customer Lifecycle Trends:** Identification of critical windows where customers are most likely to attrite.

---

## **Visual Intelligence Overview**

### **1. Executive Key Performance Indicators (KPIs)**
![KPI Overview](Images/KPI.png)
* **Analysis:** The dashboard monitors four core metrics: Total Customers (**7,043**), Churn Rate (**27%**), Total MRR (**$456.12K**), and Lost MRR (**$139.13K**).
* **Business Insight:** A **27% churn rate** indicates a significant revenue leak of **$139K**. This identifies a massive opportunity for recovery through targeted retention interventions.

### **2. Revenue Composition by Contract Type**
![Revenue by Contract](https://github.com/Fauzann79/Customer-Churn-Analysis-Retention-Strategy-Reducing-Revenue-Leakage-in-Telecommunication/blob/8d67fbfdf460dda6dd810d9df419724b3820a9e0/Images/Revenue-by-contract.png)
* **Analysis:** The donut chart reveals that **56.41% ($257K)** of total revenue is tied to **Month-to-Month** contracts.
* **Business Insight:** While this segment provides the bulk of current revenue, it is the most volatile. High concentration of short-term contracts creates a high-risk financial profile.

### **3. Loss Distribution by Internet Services**
![Loss Distribution](link_gambar_bar_chart_kamu.png)
* **Analysis:** This visualization breaks down revenue loss by service type. **Fiber Optic** users account for the highest volume of churned customers.
* **Business Insight:** The disproportionate loss in Fiber Optic suggests a potential gap in price-to-value perception or technical stability within this premium segment.

### **4. Revenue Retention vs. Leakage**
![Revenue vs Leakage]([link_gambar_stacked_bar_kamu.png](https://github.com/Fauzann79/Customer-Churn-Analysis-Retention-Strategy-Reducing-Revenue-Leakage-in-Telecommunication/blob/754a521d00c2878d100988f6549003bf1028548d/Images/revenue-vs-lost.png))
* **Analysis:** This comparison tracks held revenue versus lost revenue across contract categories.
* **Business Insight:** **Lost MRR** (dark shaded area) is almost exclusively concentrated in **Month-to-Month** contracts, validating long-term contracts as the most effective "revenue shield."

---

## **Key Business Insights**
* **Financial Exposure:** Month-to-month contracts represent the highest source of revenue loss.
* **Retention Drivers:** Customers utilizing **Technical Support** show a 3x higher retention rate compared to those without.
* **Churn Window:** The highest risk of attrition occurs within the first **0-6 months** of the customer lifecycle.

---

## **Strategic Recommendations**

### **1. Revenue Stabilization & Contract Conversion**
* **Incentivized Migration:** Launch a "Lock-in Loyalty" campaign targeting high-value Month-to-Month subscribers with a 10-15% discount for a 12-month commitment.
* **Risk-Based Pricing:** Evaluate a small premium for month-to-month flexibility to encourage the adoption of stable long-term contracts.

### **2. Service-Led Retention (Product Bundling)**
* **Technical Support Integration:** Bundle "Tech Support" as a standard feature for high-churn segments like Fiber Optic users.
* **Self-Service Support:** Invest in AI-driven self-service tools to reduce technical friction for customers.

### **3. Early Lifecycle Management (The "First 100 Days")**
* **Predictive Onboarding:** Implement an automated "Success Sequence" during the first 90 days with proactive health-check emails.
* **Early Warning System:** Use the "Risk Heatmap" to trigger automated outreach to customers exhibiting "Pre-Churn" behavior.

### **4. Payment Friction Reduction**
* **Auto-Pay Incentives:** Encourage transition from "Electronic Check" to "Auto-Pay" via a one-time bill credit to reduce manual payment failures.

---

## **Technical Resources**
* 📊 **Interactive Dashboard:** [View on NovyPro/PowerBI Service](#)
* 📁 **SQL Queries (Cleaning & Prep):** [View SQL Scripts](./SQL_Scripts)
* 📑 **Business Analysis Queries:** [View SQL Insights](./SQL_Analysis)
