# 📞 PwC Call Centre Analysis Dashboard

> An interactive Power BI dashboard analysing 5,000 call centre interactions across Q1 2021, providing insights into customer service performance, agent effectiveness, customer satisfaction, and operational efficiency.

---

## 📊 Dashboard Preview

### Executive Overview
<img width="865" height="582" alt="image" src="https://github.com/user-attachments/assets/8c2cdc4d-24c9-40df-8adc-f28a451367d9" />


### Agent Performance Analysis

---

## 🎯 Business Problem

Call centres generate large volumes of customer interaction data, but without effective reporting, it can be difficult to identify service bottlenecks, monitor agent performance, and improve customer experience.

This project analyses call centre operations between January and March 2021 to answer key business questions:

* How effectively are customer calls being handled?
* Which agents are performing best across key metrics?
* Which support topics present the biggest operational challenges?
* How satisfied are customers with the service received?
* What actions can improve overall service performance?

---

## 📈 Key Metrics at a Glance

| Metric                     | Value                |
| -------------------------- | -------------------- |
| Total Calls                | 5,000                |
| Answered Calls             | 4,054                |
| Answer Rate                | 81.1%                |
| Unanswered Calls           | 946                  |
| First Call Resolution Rate | 89.9%                |
| Average Speed of Answer    | 67.5 Seconds         |
| Average CSAT Score         | 3.40 / 5             |
| Analysis Period            | January – March 2021 |

---

## 🔍 Key Findings

### Call Centre Performance

* 81.1% of calls were successfully answered.
* 946 calls (18.9%) remained unanswered during the analysis period.
* Average speed of answer was 67.5 seconds.

### Agent Performance

* 🏆 Greg achieved the highest First Call Resolution rate (90.6%).
* 🏆 Martha recorded the highest Customer Satisfaction score (3.47/5).
* 🏆 Stewart achieved the highest Answer Rate (82.0%) and fastest response time (66.2 seconds).
* ⚠️ Joe recorded the lowest CSAT score (3.33/5) and slowest response time (71 seconds).

### Customer Satisfaction

* Overall CSAT averaged 3.40/5.
* Satisfaction scores were relatively consistent across agents and call topics.
* Admin Support achieved the highest average satisfaction score.

### Operational Insights

* Technical Support recorded the lowest resolution rate (72.2%).
* Faster response times generally aligned with stronger customer satisfaction outcomes.
* Resolution performance remained relatively consistent across all support categories.

📄 For the complete analysis and business recommendations, see:

**docs/insights_summary.md**

---

## 📊 Dashboard Features

### Executive Overview

* Total Calls
* Answer Rate
* Resolution Rate
* Customer Satisfaction Score
* Average Speed of Answer

### Agent Performance Analysis

* Calls handled by agent
* Resolution rate by agent
* Customer satisfaction by agent
* Response efficiency metrics

### Customer Experience Analysis

* CSAT trends
* Satisfaction distribution
* Satisfaction by support topic

### Operational Analysis

* Call volume trends
* Topic distribution
* Resolution effectiveness
* Service performance monitoring

---

## 🛠️ Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Data Modelling
* Data Visualisation
* Microsoft Excel

---

## 💡 Skills Demonstrated

* Data Cleaning & Transformation
* Data Modelling
* DAX Measure Development
* KPI Design
* Dashboard Development
* Business Intelligence Reporting
* Customer Experience Analytics
* Performance Analysis
* Data Storytelling
* Business Recommendations

---

## 🗂️ Repository Structure

```text
pwc-callcentre-dashboard/
│
├── data/
│   └── 01_Call-Center-Dataset.xlsx
│
├── assets/
│   └── screenshots/
│       ├── overview.png
│       └── agent-performance.png
│
├── docs/
│   └── insights_summary.md
│
├── PwC_Call_Centre_Analysis.pbix
├── README.md
└── .gitignore
```

---

## ⚙️ Getting Started

### Prerequisites

* Power BI Desktop

### Steps

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/pwc-callcentre-dashboard.git
```

2. Open `PwC_Call_Centre_Analysis.pbix`

3. Refresh the dataset if required.

4. Explore the dashboard using available filters and slicers.

---

## 📁 Dataset Information

The dataset contains 5,000 customer service interactions across 8 agents and 5 support categories.

### Key Fields

| Field               | Description                    |
| ------------------- | ------------------------------ |
| Call ID             | Unique identifier              |
| Agent               | Agent handling the call        |
| Date                | Call timestamp                 |
| Topic               | Support category               |
| Answered            | Whether the call was answered  |
| Resolved            | Whether the issue was resolved |
| Speed of Answer     | Time taken to answer the call  |
| Avg Talk Duration   | Duration of interaction        |
| Satisfaction Rating | Customer rating (1–5)          |

---

## 📌 Business Recommendations

Based on the analysis:

1. Review staffing allocation to reduce the 18.9% unanswered call rate.
2. Provide additional support and training for Technical Support teams.
3. Coach lower-performing agents using best practices from top performers.
4. Implement customer experience initiatives to improve overall CSAT beyond 4.0.

For detailed findings and supporting analysis, refer to:

📄 **docs/insights_summary.md**

---

## 🤝 Acknowledgements

This project was completed as part of my data analytics portfolio and was inspired by the PwC Power BI Virtual Experience Program.

---

## 📄 Licence

This project is intended for educational and portfolio purposes only.
