# 📂 Data

This folder contains the primary dataset and analysis workbook for the BDM Capstone Project on Hotel SR Paark, Kavali.

---

## 📁 File

### `Dataset_and_Analysis.xlsx`
- **Source:** Physical booking registers of Hotel SR Paark (primary data)
- **Period:** January 1, 2025 – December 31, 2025
- **Total Records:** ~365 daily entries across 12 monthly sheets
- **Tool Used:** Microsoft Excel

---

## 🗂️ Sheet Structure

| Sheet Name | Description |
|------------|-------------|
| `Meta Data` | Variable definitions, data types, and units for all columns |
| `January` | Daily booking data for January 2025 |
| `February` | Daily booking data for February 2025 |
| `March` | Daily booking data for March 2025 |
| `April` | Daily booking data for April 2025 |
| `May` | Daily booking data for May 2025 |
| `June` | Daily booking data for June 2025 |
| `July` | Daily booking data for July 2025 |
| `August` | Daily booking data for August 2025 |
| `September` | Daily booking data for September 2025 |
| `October` | Daily booking data for October 2025 |
| `November` | Daily booking data for November 2025 |
| `December` | Daily booking data for December 2025 |
| `MID TERM` | Aggregated monthly analysis used in mid-term report |
| `FINAL` | Comprehensive annual analysis used in final report |

---

## 📋 Variables / Columns

| Column | Description | Type | Format |
|--------|-------------|------|--------|
| `Date` | Calendar date of booking activity | Date | DD/MM/YYYY |
| `Rooms_Occupied` | Number of rooms occupied per day | Numeric | Count |
| `Total_Revenue (₹)` | Total daily revenue from rooms + services | Numeric | INR (₹) |
| `Extra_Bed_Count` | Number of extra beds requested per day | Numeric | Count |
| `Cold_Drinks_Count` | Number of cold drinks sold per day | Numeric | Count |
| `Stay_Type` | Nature of stay (Business / Family / Group / Solo) | Categorical | Text |
| `Remarks` | Operational notes (bulk bookings, events, etc.) | Text | Free text |

---

## 📊 Key Statistics

| Metric | Value |
|--------|-------|
| Average Daily Occupancy | 5.52 rooms/day (~34% of 23 rooms) |
| Average Daily Revenue | ₹12,427 |
| Revenue Range | ₹2,300 – ₹29,000 |
| Standard Deviation (Revenue) | ₹7,331 |
| Peak Month (Revenue) | May 2025 — ₹9,54,500 |
| Lowest Month (Revenue) | March 2025 — ₹1,79,900 |
| Occupancy–Add-on Correlation | r = 0.943 |

---

## 🔒 Privacy & Ethics

- No customer names, phone numbers, or personal identifiers are included
- No employee personal details are present
- Revenue and occupancy data used with **written NOC from Hotel SR Paark management**
- Data is anonymized and reported in aggregate for academic analysis only
- IIT Madras does not endorse the use of this data beyond this project

---

## 📌 Data Limitations

- Only one year of data (2025) — limits long-term forecasting accuracy
- Room rates remained largely constant throughout the year — restricts price elasticity analysis
- Manual data entry may contain minor transcription inconsistencies
- Missing entries for days with zero bookings are recorded as `0` or `No bookings`
