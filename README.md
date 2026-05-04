# Waitlist-Analysis
Power BI dashboard analyzing patient wait lists across specialties and case types (Outpatient, Day Case, Inpatient). Includes KPIs, time trends, age and time-band analysis, interactive drilldown to specialty view, and a detailed table page with flexible slicers for operational decision‑making.

## Overview
This report analyzes patient wait lists for a hospital setting to help management understand where backlogs are building, which specialties are most impacted, and how wait lists change over time. It moves from high-level KPIs to drilldown and detailed record-level analysis.

## Report Pages
- **Summary**
  - Latest and previous year month wait list KPIs.
  - Wait list split by Case Type (Outpatient, Day Case, Inpatient).
  - Wait list analysis by Time Band vs Age Profile.
  - Top 5 specialties by average/median wait list.
  - Monthly trend lines for Day Case, Inpatient, and Outpatient.

- **Specialty Drilldown**
  - Total wait list at the top.
  - Horizontal bar chart ranking specialties by total wait list.
  - Used as a drilldown from the summary to focus on specific specialties.

- **Detailed View**
  - Slicers for Archive Date, Case Type, Specialty Name, Age Profile, and Time Bands.
  - Table showing Day Case, Inpatient, Outpatient, and Total counts by date.
  - Designed for deep-dive and export-style analysis.
 
## Data & Modeling
- **Data:** [Sample / anonymized] patient wait list data.
- **Fact table:** Wait list records by date, case type, specialty, age profile, and time band.
- **Dimensions:** Date, Case Type, Specialty, Age Profile, Time Band.
- **Transformations:** Cleaned fields, handled missing values, created derived columns in Power Query.
- **DAX measures:** KPIs for latest/PY wait list, totals by case type, trend measures for monthly changes.

 ## Tech Stack
- Power BI Desktop  
- Power Query  
- DAX
