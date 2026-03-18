# 🏨 IITM-BDM-Hospitality-CaseStudy-HotelSRPaark

> **Data-Driven Optimization of Hospitality Operations: A Case Study of Hotel SR Paark, Kavali**  
> IIT Madras — BS Data Science & Applications | Business Data Management (BDM) Capstone Project

---

## 📌 Project Overview

This project analyzes the operational and revenue data of **Hotel SR Paark**, a mid-scale hospitality business located near the APSRTC Bus Stand in Kavali, Andhra Pradesh. The hotel offers 1 suite, 22 deluxe rooms, and banquet services catering to travelers, families, and corporate clients.

Using **primary data collected from physical booking registers (Jan–Dec 2025)**, this project identifies key operational inefficiencies and provides data-backed recommendations to improve occupancy, pricing, and revenue management.

---

## 🎯 Problem Statements

| # | Problem | Description |
|---|---------|-------------|
| 1 | **Occupancy & Booking Optimization** | Fluctuating room and banquet occupancy leading to underutilization on weekdays and overbooking during peak seasons |
| 2 | **Dynamic Pricing** | Static pricing strategy that doesn't reflect demand variability, limiting revenue potential |
| 3 | **Event Booking Management** | Manual booking system causing scheduling conflicts and missed revenue opportunities |

---

## 🔍 Key Findings

- 📉 Average daily occupancy: **~34%** of total room capacity (6 rooms/day out of 23)
- 📈 Peak revenue month: **May 2025 — ₹9,54,500** (wedding + summer travel season)
- 📉 Lowest revenue month: **March 2025 — ₹1,79,900**
- 💡 Strong positive correlation (**r = 0.943**) between room occupancy and add-on service usage
- 💰 Projected annual revenue gain from dynamic pricing: **₹8.82 lakh (~18–22%)**

---

## 🛠️ Methodology

| Method | Purpose |
|--------|---------|
| Descriptive Statistics | Central tendency & variability of occupancy and revenue |
| Trend & Seasonality Analysis | Monthly demand patterns using Seasonality Index |
| Occupancy Rate Analysis | % utilization of available room inventory |
| RevPAR Analysis | Revenue per Available Room for pricing efficiency |
| Dynamic Pricing Model | Demand-responsive price adjustment simulation |
| Revenue Contribution Analysis | Room vs. add-on service revenue split |
| Correlation Analysis | Occupancy vs. add-on service relationship |

**Tools Used:** Microsoft Excel (pivot tables, charts, regression, formulas)

---

## 📁 Repository Structure

```
BDM-Hotel-SR-Paark-Kavali/
│
├── README.md                        ← You are here
│
├── reports/
│   ├── proposal.pdf                 ← Project proposal (Oct 2025)
│   ├── midterm_report.pdf           ← Mid-term submission (Jan 2026)
│   └── final_report.pdf             ← Final report (Jan 2026)
│
└── presentation/
    └── BDM_PPT.pptx                 ← Project presentation slides

```

---

## 📊 Dataset Summary

- **Source:** Physical booking registers of Hotel SR Paark (primary data)
- **Period:** January 2025 – December 2025 (365 days)
- **Variables:** Date, Rooms Occupied, Total Revenue (₹), Extra Bed Count, Cold Drinks Count, Stay Type, Remarks
- **Privacy:** No personally identifiable customer or employee information included
- **NOC:** Data used with written permission from Hotel SR Paark management

---

## 💡 Recommendations

1. **Weekday Discount Pricing** — 10–15% off on weekdays when occupancy < 50%
2. **Occupancy-Based Price Adjustment** — 10–20% rate hike during peak demand months
3. **Add-on Service Bundling** — Room + Extra Bed / Room + Cold Drinks packages at check-in
4. **Flexible Walk-in Pricing** — Controlled discounts (max 15%) for walk-ins on low-demand days
5. **Weekday Banquet Pricing** — Lower banquet rates on weekdays to attract corporate/local events
6. **Customer Loyalty Program** — Repeat stay incentives (5% off or free add-on)
7. **Digital Record Keeping** — Standardized Excel-based daily tracking for better forecasting

---

## 👤 Author

**Mannepalli Bala Praharsha**  
Roll No.: 24F1002193  
📧 24F1002193@ds.study.iitm.ac.in  
🔗 [LinkedIn](https://linkedin.com/in/mannepalli-bala-praharsha) | [GitHub](https://github.com/balapraharsha)  
IIT Madras — BS Data Science & Applications

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).  
All recommendations are business-specific and intended solely for academic purposes.  
IIT Madras does not endorse the findings or recommendations of this project.

---

> *"Without data, you're just another person with an opinion."* — W. Edwards Deming
