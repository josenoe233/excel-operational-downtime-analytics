# excel-operational-downtime-analytics
End-to-end operational downtime analytics system built in Excel for maintenance performance analysis and decision support.


## 🧩 What is it?

This project is an operational analytics system developed in Excel to monitor, analyze, and evaluate the performance of production equipment (Casting area) through maintenance and reliability KPIs.

The system integrates:
- Structured downtime event recording
- Historical and auditable database
- Daily, weekly, and monthly analysis
- Automatic calculation of industrial KPIs
- Clear dashboards focused on managerial decision-making

The entire analytical layer is built using Excel formulas, ensuring full control, traceability, and model stability.


## 🎯 Objective

Transform operational downtime records into actionable information for maintenance, production, and management teams.

Key objectives:
- Measure the real impact of downtime by equipment and group
- Identify failure trends
- Compare performance across shifts, days, weeks, and months
- Evaluate operational availability and reliability
- Support preventive and corrective maintenance decisions

## ❓ Why it matters

In industrial environments, unmeasured downtime directly translates into financial loss.

This system enables:
- Identification of critical equipment
- Reduction of downtime through data-driven actions
- Maintenance prioritization based on impact
- Justification of decisions using reliable metrics
- Improvement of Operational Availability (OA)

Additionally:
- Eliminates subjective analysis
- Reduces dependency on manual reports
- Establishes a common data language between production and maintenance
- 
## 🔍 What does it analyze?

### 🏭 Equipment / Machine level
- Downtime hours
- Number of downtime events
- Downtime impact (Yes / No)
- Downtime percentage
- MTTR
- MTBF
- Operational Availability (OA)

### 📅 Time level
- Daily analysis
- Weekly analysis (real calendar week)
- Monthly analysis using dynamic calendar
- Automatic exclusion of future dates

### 👥 Organizational level
- Group-based analysis
- Group comparison
- Overall consolidation


## 📐 KPIs calculated

The system automatically calculates:

- Downtime hours
- Number of downtime events
- Downtime percentage
- **MTTR (Mean Time To Repair)**  
  Calculated as total downtime hours divided by number of events
- **MTBF (Mean Time Between Failures)**  
  Calculated using a weighted approach, not a simple average
- **Operational Availability (OA)**

All KPIs:
- Exclude future dates
- Ignore artificial zeros
- Reduce statistical bias
- Follow maintenance and reliability best practices


## ⚙️ System architecture

- **Downtime input form**  
  Structured capture of downtime events with controlled inputs

- **Central database**  
  Historical, normalized, and auditable downtime records

- **Analytical layers**
  - Daily dashboards
  - Weekly analysis
  - Monthly analysis

Dashboards are built using Excel formulas such as:
- SUMIFS
- COUNTIFS
- IFERROR
- AVERAGEIFS
- Weighted calculations

## 🧠 Decisions it supports

This system helps answer questions such as:
- Which equipment generates the highest downtime impact?
- Are issues driven by frequency or repair duration?
- Which groups have the lowest availability?
- Where should preventive maintenance be prioritized?
- Which weeks concentrate the highest operational impact?
- How does performance evolve over time?


## 🛠 Tools & skills demonstrated

- Advanced Excel formulas
- VBA macros for automation and control
- Structured data modeling
- Maintenance and reliability KPIs (MTTR, MTBF, OA)
- Operational analytics
- Dashboard design for decision support



## 📸 Screenshots

### Downtime input form
![Input Form](images/01_input_form.png)

### Generated PDF for audit and traceability
![Generated PDF](images/Hoja de paro (Semana 53, Mes 12, Año 2025, Folio 4444442))

### Historical database structure
![Database](images/03_database.png)

### Daily analysis by machines
![Daily Machines](images/04_daily_machines.png)

### Furnace performance analysis
![Furnaces](images/05_furnaces.png)

### Monthly group calendar analysis
![Group Calendar](images/07_group_calendar.png)

### Weekly group analysis
![Weekly Groups](images/08_weekly_groups.png)

### Exploratory analysis with pivot tables
![Pivot Analysis](images/09_pivot_analysis.png)


## 🎥 Demo video

A short walkthrough video explaining the system architecture, dashboards, and analytical value will be added soon.

## 🚀 Future improvements

- Automated report distribution
- Power BI integration
- Automatic data ingestion from ERP systems
- Alerting based on critical thresholds
- Predictive failure analysis
