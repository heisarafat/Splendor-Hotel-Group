# Splendor-Hotel-Group
# 📊 Splendor Hotel Group Booking Data Analysis

Welcome to the **SHG Booking Data Analysis** project. This repository showcases a comprehensive exploratory data analysis (EDA) of historical booking data for the renowned **Splendor Hotel Groups (SHG)**, aimed at uncovering business insights and improving operational efficiency using data-driven strategies.

---

## 📌 Project Summary

As a newly recruited Data Analyst at SHG, I was tasked with analyzing historical booking data from one of SHG’s top-performing resorts. The goal is to extract actionable insights that would:
- Improve guest experience,
- Inform pricing and marketing strategies,
- Streamline internal operations, and
- Optimize revenue channels.

---

## 🎯 Analysis Objectives

The analysis is structured around several business-critical areas:

- **Booking Patterns:** Time trends, seasonality, and lead time by channel.
- **Customer Behavior:** Distribution channels, country of origin, and ADR patterns.
- **Cancellations:** Correlations, predictive indicators, and revenue impact.
- **Revenue Optimization:** Segment-level analysis and pricing strategy suggestions.
- **Geographical Insights:** Target markets and country-level behaviors.
- **Operational Efficiency:** Stay duration, check-out trends, staffing implications.
- **Deposit Impact:** Role of deposits in cancellations and revenue security.
- **Corporate Bookings:** Characteristics and trends.
- **Time-to-Event Analysis:** Impact of lead time on behavior and revenue.
- **Agent Comparison:** Online vs. offline agent performance.

> _Only the **3/10** section has been completed so far. Other sections will be added incrementally._

---

## 🧾 Dataset Overview

| Column | Description |
|--------|-------------|
| Booking ID | Unique booking identifier |
| Hotel | Hotel name/type |
| Booking Date | Date when booking was made |
| Arrival Date | Check-in date |
| Lead Time | Days between booking and arrival |
| Nights | Duration of stay |
| Guests | Number of guests |
| Distribution Channel | Source of booking |
| Customer Type | e.g., Corporate, Transient |
| Country | Guest's country of origin |
| Deposit Type | Deposit made or not |
| Avg Daily Rate | Booking’s daily rate |
| Status | Booking outcome |
| Status Update | Last update on booking status |
| Canceled (0/1) | Indicator for cancellation |
| Revenue | Revenue generated |
| Revenue Loss | Estimated revenue lost from cancellations |

---

## 🛠️ Tools & Technologies

- 🐍 **Python** (Pandas, Matplotlib, Seaborn) – Data cleaning & EDA  
- 📊 **Power BI** – Visual dashboards *(in progress)*  
- 📒 **Notion** – Project documentation  
- 📈 **Excel** – Early exploration and data validation  

## 📄 License
### This project is for educational and portfolio purposes only. Dataset used may be anonymized or synthetic to respect data privacy.

### 🤝 Connect With Me
### Arafah Ibitoye
#### 🎓 Industrial Chemist & Junior Data Analyst
### 🌍 Nigeria | 📧 [arafahibitoye@gmail.com]
### 🔗 LinkedIn Profile: www.linkedin.com/in/arafahibitoye
### Notion: https://www.notion.so/Splendor-Hotel-Group-Booking-Data-Analysis-229bd9a9804880b8a097dd04a464082e?source=copy_link\


⭐ Acknowledgements
Thanks to Splendor Hotel Groups (SHG) for the case scenario and dataset framework, and to open-source communities supporting learning in Data Science and Business Analytics.
---

## 📁 Repository Structure

```bash
SHG-Booking-EDA/
│
├── data/
│   └── shg_bookings.csv                 # Sample dataset
│   └── shg_cleaned dataset.csv          # Cleaned dataset
|
├── notebooks/
|   └── 01-Splendor Hotel Group Data cleaning.ipynb       # Data Cleaning
│   └── 02-booking-patterns.ipynb        # EDA for booking patterns
│   └── 03-customer-behavior.ipynb       # (pending)
│
├── visuals/
│   └── booking_trend_by_month.png       # Static chart files
│
├── dashboard/
│   └── powerbi-dashboard.pbix         (Coming Soon)
│
├── docs/
│   └── project-report.pdf   (Coming Soon)            
│
└── README.md                            # Project overview






