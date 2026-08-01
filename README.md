# 📊 Bank Marketing Campaign Analysis Dashboard

An end-to-end Tableau dashboard project that analyzes a real-world bank marketing campaign dataset to uncover the factors influencing term deposit subscriptions. The project transforms raw campaign data into interactive visual dashboards, enabling business users to evaluate campaign performance, identify conversion drivers, and make data-driven marketing decisions.

---

## 📌 Project Overview

Banks invest significant resources in telemarketing campaigns to promote term deposits. However, understanding which customers are most likely to subscribe and which campaign strategies are effective is challenging when working with large volumes of raw data.

This project addresses that challenge by developing **two interconnected Tableau dashboards**:

- **Dashboard 1:** What happened during the campaign?
- **Dashboard 2:** Why did it happen and what actions should be taken?

Together, these dashboards provide both descriptive and diagnostic analytics for marketing decision-making.

---

## 🎯 Business Problem

Marketing teams often struggle to determine:

- Which customer segments respond best to campaigns.
- Which contact methods produce higher conversions.
- How many follow-up attempts are effective.
- Whether previous campaign interactions influence future subscriptions.
- Which campaign strategies should be improved.

This dashboard converts complex marketing data into meaningful business insights.

---

## 📂 Dataset

**Source:** UCI Machine Learning Repository

**Dataset:** Bank Marketing Dataset

**Records:** 45,211 Customers

**Features:** 17 Attributes

The dataset contains customer demographic information, financial profile, campaign history, contact details, and subscription outcomes.

---

## 🛠 Tools Used

- Tableau Public
- Microsoft Excel
- GitHub

---

# 📈 Dashboard 1 – Campaign Performance Overview

### Purpose

Provides a high-level overview of campaign performance and customer distribution.

### KPIs

- Total Customers
- Subscription Rate
- Average Balance
- Average Call Duration
- Average Contacts per Customer

### Visualizations

- Subscription Rate by Job
- Customer Distribution by Contact Type
- Loan Status vs Subscription Rate
- Previous Campaign Outcome Distribution
- Monthly Marketing Activity
- Subscription Rate by Education
- Contact Type vs Month Heatmap

### Business Questions Answered

- Which customer groups subscribe the most?
- Which contact channel performs better?
- How does education influence subscription?
- Which months had the highest campaign activity?

---

# 🔍 Dashboard 2 – Root Cause Analysis

### Purpose

Explains why the campaign achieved its results and identifies optimization opportunities.

### KPIs

- Previous Campaign Success Rate
- Customers Recontacted
- Average Days Before Recontact
- Average Contacts (Subscribers vs Non-Subscribers)

### Visualizations

- Campaign Intensity by Job
- Contact Recency vs Subscription Rate
- Campaign Contacts vs Subscription Rate
- Average Balance by Job
- Subscription Rate by Marital Status
- Call Duration Comparison (Subscribers vs Non-Subscribers)

### Business Questions Answered

- Does increasing contact frequency improve conversion?
- How does recontact timing influence subscriptions?
- Which customer segments deserve higher priority?
- How does call duration differ between subscribers and non-subscribers?

---

# 💡 Key Insights

- Students recorded the highest subscription rate among all occupations.
- Cellular communication generated the largest share of successful contacts.
- Higher campaign contact frequency showed diminishing conversion returns.
- Subscribers generally experienced longer call durations than non-subscribers.
- Customer demographics such as job, education, and marital status significantly influenced campaign success.
- Previous campaign success positively impacted future subscription probability.

---

# 📊 Recommendations

- Prioritize customer segments with historically higher subscription rates.
- Focus campaigns on cellular communication where possible.
- Avoid excessive follow-up calls, as conversion decreases after multiple contacts.
- Schedule recontacts strategically based on previous campaign history.
- Use dashboard insights to optimize customer targeting and campaign planning.

---

# ⚠ Data Quality Note

One important limitation of this dataset is the **"unknown" category** in the **Previous Campaign Outcome (`poutcome`)** field.

A large number of records are labeled as **"unknown"**, indicating that previous campaign information was unavailable rather than representing an actual campaign outcome.

This should **not** be interpreted as campaign failure or success. Instead, it reflects **missing historical information**, which may affect analyses involving previous campaign performance.

The dashboard presents this category transparently so that users can interpret the results correctly.

---

# 🌐 Tableau Dashboard

🔗 **Interactive Dashboard:**

**Dashboard 1** - https://public.tableau.com/app/profile/kritika.singh4876/viz/BankMarketingCampaignAnalysisDashboard1/Dashboard1
**Dashboard 2** - https://public.tableau.com/app/profile/kritika.singh4876/viz/BankMarketingCampaignAnalysisDashboard2/Dashboard2 


---

# 📸 Dashboard Preview

## Dashboard 1


## Dashboard 2



---

# 📁 Repository Structure

```
Bank-Marketing-Campaign-Analysis
│
├── README.md
├── Bank_Marketing_Dataset.csv
├── dashboard1.png
├── dashboard2.png
├── Concept_Note.pdf
├── Final_Presentation.pptx
└── Tableau_Dashboard.twbx
```

---

