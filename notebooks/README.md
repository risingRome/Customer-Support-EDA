# Customer Support Ticket Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a customer support ticket dataset to uncover patterns in ticket volume, ticket priorities, response times, resolution times, and customer satisfaction.

The objective is to identify operational insights that can help improve customer support efficiency and service quality.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Dataset Features

The dataset contains the following fields:

* Ticket ID
* Customer Name
* Customer Age
* Customer Gender
* Product Purchased
* Date of Purchase
* Ticket Type
* Ticket Subject
* Ticket Description
* Ticket Status
* Resolution
* Ticket Priority
* Ticket Channel
* First Response Time
* Time to Resolution
* Customer Satisfaction Rating

---

## Analysis Performed

### Data Cleaning

* Missing value analysis
* Date and time conversion
* Feature engineering for response and resolution hours

### Exploratory Data Analysis

* Ticket Status Distribution
* Ticket Priority Distribution
* Ticket Type Analysis
* Ticket Channel Analysis
* Customer Age Distribution
* Response Time Analysis
* Resolution Time Analysis
* Customer Satisfaction Analysis

### Correlation Analysis

* Customer Age
* First Response Hours
* Resolution Hours
* Customer Satisfaction Rating

---

## Key Findings

* Support workload was distributed across multiple ticket categories and channels.
* Critical and High priority tickets represented a significant portion of support activity.
* Response time and resolution time showed a very strong positive correlation.
* Customer age had almost no impact on customer satisfaction.
* Customer satisfaction was only weakly related to response and resolution speed.

---

## Project Structure

```text
Customer-Support-EDA/
│
├── archive/
│   └── customer_support_tickets.csv.csv
│
├── data/
├── images/
├── notebooks/
│   └── customer_support_eda.ipynb
│
├── README.md
├── requirements.txt
└── insights_summary.md
```

---

## Future Improvements

* Build an interactive dashboard using Power BI or Streamlit.
* Predict ticket resolution times using Machine Learning.
* Create automated reporting for support managers.
* Analyze customer sentiment from ticket descriptions.

---

## Author

**Rahul Raj**

Aspiring Data Analyst | Python | SQL | Power BI | .NET Development
