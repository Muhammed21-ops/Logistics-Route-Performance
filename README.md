# Logistics Route & Vehicle Planning Dashboard (Power BI)

## Project Overview
A logistics company operating across Istanbul needed a smarter way to plan daily vehicle deployment. Manual planning was leading to over-allocation of vehicles, underutilized capacity, and no visibility into which districts were driving the most delivery volume.
I analyzed the full delivery operation — 1,000+ daily orders across 11 districts — and built a Power BI dashboard that automatically calculates the exact number of vehicles required based on real volume, route structure, and capacity constraints.
The dashboard gives operations managers a single screen to make daily fleet decisions instead of relying on spreadsheets or guesswork. 
---

## Case Study Context
This project is based on a logistics case study where specific operational constraints were provided.

The objective was to calculate the number of vehicles required to execute daily deliveries efficiently by analyzing:
- total delivery volume (m³)
- number of routes and drop density
- vehicle capacity limitations
- district-based distribution structure

---

## Business Problem
In logistics operations, poor capacity planning and inefficient routing can result in:
- excessive vehicle usage
- underutilized capacity
- increased transportation costs
- lack of visibility in operational planning

This project addresses these challenges by providing a data-driven approach to vehicle planning and route evaluation.

---


## What I delivered:

- Automated vehicle requirement engine — calculates fleet size from volume and capacity constraints across three vehicle types (7m³, 10m³, 15m³)
- District-level breakdown table — volume, drop count, and required vehicles per district (Kadıköy, Üsküdar, Maltepe, Pendik, Kartal and 6 more)
- Geographic map visualization — delivery density plotted across Istanbul using color-coded district markers
- Interactive KPI cards — Total Orders, Total Volume, Drop Count, Drop Rate, Required Vehicles, Volume Utilization
- Dynamic filtering — by date, region (Anadolu / Avrupa), and district
---

## Business Impact
- Eliminated vehicle over-allocation by matching capacity precisely to daily demand
- Identified Kadıköy as the highest-density district (283 drops, 114m³) — enabling priority resource planning
- Reduced planning time from manual calculation to a single dashboard view
- Built for scale — supports both Istanbul Anadolu and Istanbul Avrupa side operations

---

## Approach
- Calculated required vehicle count based on volume and capacity constraints
- Analyzed route structure and delivery distribution across districts
- Evaluated drop rate to understand delivery density
- Built KPI-based logic to monitor operational efficiency
- Designed a dashboard to support planning and decision-making

Tools used: Power BI · DAX · Data Modeling · Excel
---

## Key Metrics
- Total Orders
- Total Volume (m³)
- Drop Count
- Drop Rate
- Required Vehicles
- Volume Utilization (%)
- Vehicle Type Distribution (7m³, 10m³, 15m³)

---

## Key Findings

- Kadıköy is the highest-pressure district with 283 drops and 19 required vehicles — over 2× the average district load- 
- Vehicle mix optimization: 78 small (7m³) vehicles + 6 medium (10m³) vehicles achieved near-perfect 99.98% volume utilization
- Anadolu4 group drives the highest total volume (243.5 m³) — nearly double the next group (Anadolu5 at 143.1 m³)
- Routing structure reveals significant imbalance between groups, creating opportunity to redistribute load and reduce total vehicle count

## Dashboard Features
- KPI cards for operational performance tracking
- district-based delivery analysis
- route and group-level breakdown
- map visualization for geographic distribution
- dynamic filtering (date, region, district)
- vehicle requirement and capacity analysis

---

## Key Findings
- Identified districts with high drop density but inefficient vehicle allocation
- Detected imbalance between delivery volume and assigned vehicle capacity
- Highlighted routing inefficiencies affecting vehicle utilization
- Revealed opportunities to optimize vehicle planning and reduce unnecessary usage

---

## Key Results

Metric                              Result
Total daily orders analyzed         1,000+
Total delivery volume               605.88 m³
Required vehicles calculated        84 (78 × 7m³, 6 × 10m³)
Volume utilization achieved         99.98%
Districts covered                   11 (Istanbul Anadolu & Avrupa)
Drop rate                           99%

## Business Impact
- Supports accurate vehicle planning for daily operations
- Helps reduce unnecessary vehicle allocation
- Improves capacity utilization and routing efficiency
- Enables data-driven decision-making in logistics operations

---

## My Role
- Designed the analytical structure of the case study
- Defined KPI logic and business metrics
- Built the data model using Power BI
- Developed DAX calculations for operational KPIs
- Created interactive dashboards for decision support

---

## Tools Used
- Power BI
- DAX
- Excel
- Data Modeling

---

## Notes
This project is created as a case-based portfolio study.  
All data has been anonymized or simulated for demonstration purposes.
