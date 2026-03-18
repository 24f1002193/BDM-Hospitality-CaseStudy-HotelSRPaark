# IITM-BDM-Hospitality-CaseStudy-HotelSRPaark

A Business Data Management capstone project submitted to IIT Madras as part of the BS Data Science & Applications programme. This project applies structured data analysis to uncover operational inefficiencies and revenue gaps in a real-world hospitality business, and proposes evidence-based strategies for improvement.

---

## About the Project

The hospitality industry, particularly small and mid-scale hotels in tier-2 cities, often operates without structured data systems. Decisions around pricing, staffing, and room allocation are largely driven by observation and intuition rather than data. This project addresses that gap by building a data-driven framework for a functioning hotel business.

Primary data was collected directly from the hotel's physical booking registers over an entire calendar year, digitized, cleaned, and analyzed using Microsoft Excel. The outcome is a set of practical, implementable recommendations tailored to the specific operational context of the business.

---

## Problem Areas Addressed

**Occupancy Optimization**
Room and banquet occupancy fluctuates significantly across the year — heavily underutilized on weekdays and during the first quarter, while facing high demand pressure during summer and festive seasons. The absence of demand forecasting or structured booking data makes it difficult to plan resources efficiently.

**Revenue Management**
The hotel follows a fixed pricing model throughout the year regardless of demand conditions. This means revenue is not maximized during high-demand periods and no incentive exists to stimulate bookings during low-demand periods, resulting in wide revenue swings across months.

**Event Booking Inefficiency**
Banquet and event bookings are managed manually, leading to scheduling conflicts, missed opportunities, and no visibility into booking trends over time.

---

## Analytical Approach

The project follows a structured methodology combining qualitative observation with quantitative data analysis:

- **Descriptive Statistics** — Establishes baseline performance benchmarks across occupancy, revenue, and add-on service usage
- **Trend & Seasonality Analysis** — Identifies monthly and quarterly demand cycles using a seasonality index
- **Occupancy Rate Analysis** — Measures daily and monthly capacity utilization against total available rooms
- **RevPAR (Revenue per Available Room)** — Evaluates how effectively each available room is being monetized
- **Correlation Analysis** — Examines the relationship between room occupancy and add-on service consumption
- **Dynamic Pricing Simulation** — Models the projected revenue impact of demand-responsive pricing adjustments
- **Revenue Contribution Analysis** — Breaks down total revenue into room revenue and auxiliary service revenue

All analysis was performed in Microsoft Excel using pivot tables, formulas, charts, and regression tools.

---

## Key Outcomes

The analysis revealed a consistent pattern of seasonal demand imbalance, with the hotel generating a disproportionate share of annual revenue during a small window of peak months. Average daily occupancy remained well below capacity for most of the year, and add-on service revenue was found to be entirely dependent on occupancy levels rather than independent guest purchasing behavior — indicating the absence of any upselling strategy.

A dynamic pricing simulation demonstrated that demand-responsive rate adjustments, combined with targeted weekday promotions and add-on bundling, could meaningfully improve annual revenue without increasing operational costs.

---

## Repository Structure

```
├── README.md
├── reports/
│   ├── proposal.pdf
│   ├── midterm_report.pdf
│   └── final_report.pdf
└── presentation/
    └── BDM_PPT.pptx

```

---

## License

MIT License
