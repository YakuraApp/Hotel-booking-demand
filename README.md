# Hotel Booking Cancellation Analysis & Revenue Optimization

## 📊 Final Analysis Notebook

[View Final Notebook](./final.ipynb)

## Project Overview

This project analyzes hotel booking data to identify key drivers of cancellations and quantify their impact on revenue. The objective is to provide clear, data-driven strategies that reduce cancellations and improve profitability.

---

## Approach

### 1. Data Cleaning & Preparation

* Handled missing values (e.g., dropped high-missing columns, filled key fields)
* Encoded categorical variables for modeling
* Ensured data quality for accurate analysis and predictions

### 2. Exploratory Data Analysis (EDA)

* Identified cancellation rate (~37%) as a major business issue
* Analyzed key drivers:

  * **Lead Time:** Customers who cancel book ~2x earlier
  * **Deposit Type:** No-deposit bookings drive most cancellations
  * **Market Segment:** Online TA and Groups are high-risk segments

### 3. Business-Focused Insights

* High-volume segments (Online TA) create the largest revenue risk
* Groups segment has extremely high cancellation rates (~61%)
* Flexible booking policies significantly increase cancellation likelihood

---

## Machine Learning Model

A **Random Forest model** was built to predict the likelihood of cancellations based on customer and booking behavior.

### Key Drivers Identified:

* Lead time
* Average daily rate (ADR)
* Deposit type (Non-refundable vs No deposit)
* Special requests
* Market segment

This model allows the business to **proactively identify high-risk bookings before cancellation occurs**.

---

## Business Impact Simulation

Using model predictions:

* High-risk bookings were identified (top 20%)
* Simulated targeted intervention (deposit enforcement)
* Estimated revenue recovery:

<span style="color:green; font-weight:bold; font-size:18px;">
$704,680.97 in recovered revenue
</span>

---

## Actionable Strategy

**Do this:**

* Require **non-refundable or partial deposits** for bookings flagged as high-risk
  (long lead times + Online TA / Groups segments)

**Then:**

* Reduce cancellation rates in the highest-risk segments
* Increase confirmed stays
* Improve revenue predictability

---

## Value for Shareholders

* Direct reduction in revenue loss from cancellations
* More stable and predictable booking pipeline
* Data-driven decision-making for pricing and policy strategies

This project demonstrates how combining **analytics + machine learning + clear business communication** can drive measurable financial impact.
