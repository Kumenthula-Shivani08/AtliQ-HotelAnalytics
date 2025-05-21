# AtliQ Grands Hospitality Data Analysis

## Problem Statement
AtliQ Grands, a luxury hotel chain with 20 years of experience, is facing a decline in revenue and market share due to rising competition and poor management.They lack an in-house data analytics team to extract insights from their historical data.To address these challenges, they plan to hire a third-party service provider for data-driven analysis.This approach aims to optimize booking trends, room performance, and overall revenue.A project focused on analyzing hotel booking trends, room performance, and revenue optimization for AtliQ Grands, a luxury hotel chain with 20 years of experience.

---

## ✅ Project Aims

- Analyze hotel and room category performance across different cities.  
- Understand customer booking behavior by time and platform.  
- Identify trends in occupancy, cancellations, and revenue realization.  
- Detect seasonal trends and identify top- and low-performing properties.  
- Recommend data-driven strategies to increase occupancy and revenue.
  
## 🛠️ Tools Used

- **Power BI Desktop** – Building interactive dashboards and reports with DAX-based KPIs.  
- **Power Query Editor** – Data cleaning and transformation within Power BI.  
- **DAX** – Calculating key metrics like Revenue, ADR, RevPAR, and creating calculated columns such as day types.  
- **Microsoft Excel** – Initial data cleaning and validation before analysis.  


## 📁 Data Sources

All datasets are in CSV format, covering various dimensions and facts related to hotel bookings:
| File Name                    | Description                             |
|------------------------------|---------------------------------------|
| `dim_date.csv`               | Dates with day, week, month, and year |
| `dim_hotels.csv`             | Hotel details like name, city, and type |
| `dim_rooms.csv`              | Types of rooms and their prices        |
| `fact_bookings.csv`          | Records of each booking                 |
| `fact_aggregated_bookings.csv` | Summary of booking data and key numbers |


---
## 📌 Key Metrics

| Metric           | Description                                                                                  |
|------------------|----------------------------------------------------------------------------------------------|
| Revenue          | Total income from bookings.                                                                  |
| RevPAR           | Revenue per available room (`Revenue / Total Capacity` or `ADR * Occupancy %`).              |
| ADR              | Average Daily Rate per sold room (`Revenue / Total Bookings`).                               |
| Cancellation     | Total number of booking cancellations.                                                      |
| Occupancy %      | Percentage of rooms booked (`Total Successful Bookings / Total Capacity`).                    |
| Cancellation %   | Percentage of bookings cancelled.                                                           |
| SRN              | Sellable Room Nights – total rooms available for sale after exclusions.                      |
| DSRN             | Daily Sellable Room Nights.                                                                  |
| URN              | Utilized Room Nights – nights actually stayed by customers.                                 |
| DURN             | Daily Utilized Room Nights.                                                                  |
| BRN              | Booked Room Nights (`URN + Cancellations + No Shows`).                                      |
| DBRN             | Daily Booked Room Nights.                                                                    |
| Realisation      | Booking realization rate (`URN / BRN`).                                                     |
| Avg Rating       | Average customer rating per booking.                                                        |
| Day Type         | Day categorized as Weekday (Sun–Thu) or Weekend (Fri–Sat).                                  |
| Booking Platforms| Booking channels including AtliQ’s own and 6 major third-party platforms.                    |
| Week Number      | Week of the calendar year.                                                                   |
| WoW              | Week-on-Week performance change.                                                            |

---

