# Aurora-Bank-Analysis----PowerBI---
## I. Introduction

### 1. Inrtoduction to Dataset
  Dataset: Aurora Bank
  
  Dataset stores customer data, financial products, transactions, payment units, and the bank’s credit risk data.
  
  The dataset consists of four tables:
  
- Users Data – contains customer information.

- Cards Data – includes information about financial products.

- MCC Codes Data – contains information about payment merchants and merchant category codes.

- Transactions Data – records transaction details over time.
### 2. Business Requirement
Build a banking analytics dashboard focusing on customer segmentation, transaction performance across payment units, and credit risk analysis.

The objective is to identify potential customer segments, detect low-performing areas, and determine factors that increase non-performing loans, in order to propose strategies to improve credit quality.

## II. Design Thinking Method

Here is 4 steps of design thinking

### Step 1: Empathize

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/3f2cc6ec-83fd-47d0-b760-38dadc1d6e15" />

<img width="1509" height="1042" alt="image" src="https://github.com/user-attachments/assets/c8f416cd-a727-4ef0-96e9-062381bc29c0" />

<img width="1122" height="1402" alt="image" src="https://github.com/user-attachments/assets/baec6338-036f-4be9-940f-3fa9535d998a" />

### Step 2: Define

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/30ab74d7-f5fc-4f21-851d-2317eeb44d39" />

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/13eeaaca-2fa9-4e06-88df-e42907905c47" />

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/aa51bf3a-efe7-4725-b323-98193e4ef2ff" />

## III. Visualization

### Overview

<img width="1270" height="730" alt="image" src="https://github.com/user-attachments/assets/ec91cbf0-b799-43d7-9185-2ed55b91bd5e" />

### 📌 Key Insights
- Female customers contribute slightly more transaction value than male customers.
- Customers aged 35–55 represent the most valuable customer segment with stable spending behavior.
- Customers under 25 show high credit utilization despite lower income levels, indicating potential future credit risk.
- Middle-income customers ($30K–$60K) show the highest bad debt ratio.
- Medium-risk and high-risk customer groups account for a significant portion of the portfolio.

### Transaction Analysis

<img width="1263" height="712" alt="image" src="https://github.com/user-attachments/assets/d755393c-3ee7-4421-b86d-bb0cd9ae0d43" />

### 📌 Key Insights
- Total transaction amount increased approximately **54% YoY**, mainly driven by higher transaction frequency.
- Peak transaction periods occur between:
  - **9:00–14:00**
  - **19:00–22:00**
- Grocery stores, utilities, and money-transfer services dominate transaction activities.
- Chip transactions maintain the lowest system error rates compared to online and swipe transactions.
- Online transaction error rates increased over time.

### Risk Analysis

<img width="1258" height="726" alt="image" src="https://github.com/user-attachments/assets/18c4a795-9f4a-447a-932a-57c5f124eec1" />

### 📌 Key Insights
- High-risk transactions continue increasing over time, indicating worsening portfolio quality.
- Customers aged **25–34** have the highest Debt-to-Income (DTI) ratio and higher default risk.
- Debt-to-Income ratio and Credit Utilization are the strongest indicators of financial risk.
- Utility and money-transfer transactions may signal early financial distress behavior.
- High-risk activities are concentrated in utilities, telecommunications, and money-transfer merchants.

### Card Analysis

<img width="1270" height="713" alt="image" src="https://github.com/user-attachments/assets/3782ff88-3fd3-4ab7-af18-80f9f8d3c376" />

### 📌 Key Insights
- Mastercard and Visa dominate transaction volume, reflecting a mass-market customer base.
- Many customers hold multiple cards but generate relatively low spending levels.
- Card issuance exceeds actual usage, increasing inactive credit exposure risk.
- Most customers prefer chip-enabled cards due to higher security and lower error rates.
- System error rates differ across card brands.

### Customers Analysis

<img width="1222" height="706" alt="image" src="https://github.com/user-attachments/assets/276508dc-be06-4cf3-9cc8-e1d281b2aab7" />


## V. Recommend
### 📌 Transaction Growth
- Increase transaction frequency through cashback campaigns and digital payment incentives.
- Improve online transaction infrastructure to reduce rising system error rates.

### 📌 Customer Segmentation
- Prioritize customers aged 35–55 as the primary revenue-generating segment.
- Develop financial education programs for younger customers with high utilization behavior.

### 📌 Credit Risk Management
- Closely monitor customers with high DTI and high credit utilization ratios.
- Build early-warning systems for abnormal money-transfer and utility-payment activities.
- Strengthen monitoring for middle-income customers due to elevated bad debt risk.

###📌 Card Portfolio Optimization
- Reduce inactive card exposure by reviewing unused credit limits.
- Increase customer engagement to position Aurora Bank as the primary card provider.

### 📌 Operational Improvement
- Optimize system performance during peak transaction hours.
- Encourage chip/contactless transactions due to lower operational error rates.



