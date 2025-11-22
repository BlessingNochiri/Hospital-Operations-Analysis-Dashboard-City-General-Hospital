# Hospital-Operations-Analysis-Dashboard-City-General-Hospital
**Author:** Blessing Shantel Nochiri
**Date:** 2025-11-22 

--- 

## Project Background 
City General Hospital is experiencing Unexplained patient surge overwhelming the ER, compounded by a demographic mismatch, Severe staffing mismanagement, 
with dangerous overwork for some doctors, Pharmacy ordering errors, loss of money due to improper insurance payments and high lab retest 
rates. This project analyzes available hospital data and produces an interactive Excel dashboard with actionable recommendations. 

--- 

## Project Objective 
- Determine the age group distribution of our patient population.
- Analyze the average billing amount received from insurance providers.
- Identify top doctors associated with patients experiencing long lengths of stay, and understand LOS distribution by admission type.
- Uncover the most frequently prescribed medications over time and their associated.
- Evaluate the proportion of abnormal, normal, and inconclusive test results.
- Recommend prioritized actions to stabilize hospital operations 

--- 

## Datasets 
- **City Hospital Dataset**
- patient_id, age, age group, gender, Blood Type, Medical Condition, Date of Admission, Admission month, Doctor, Hospital, Insurance Provider,
  Billing Amount, Room Number, Admission Type, Discharge Date, Medication, Test Results, Hospital Latitude, Hospital Longitude, Length of Stay,
  LOS category, Billing Per Day.
 
--- 

## Dashboard Features 
- Key KPIs: total patients, Total Doctors, Avg. Length of Stay, Avg. Length of Stay, Sum Billing Amount
- Visuals: Billing Amount by Insurance Provider chart, age-group distributions, Top Medication Prescribed over Time,
  Test Quality proportion, Hospital Bottleneck (over-crowding) distribution

- Interactivity: slicers/filters Admission type, medical condition, Age group, Test result, Admission Month 

--- 

## Key Findings
- Majority of ER visits are from elderly patients → contributes to bed shortages
- Uneven staff distribution: some departments overloaded while others idle
- Inventory mismatch: critical drugs short while others near expiry
- 15% of lab tests flagged for retest, increasing workload and delays
- Revenue leakage from unpaid insurance claims and billing gaps 

--- 

## Recommendations 
1.analyze historical admission data to identify seasonal trends and demographic shifts. By creating a predictive model, 
we can forecast patient surges and age demographics accurately. 
2. Conduct a "Time and Motion" study using the staffing data. We need to correlate staff schedules with peak patient arrival times. 
3. Perform an ABC Analysis on inventory data to classify high-value and high-turnover drugs. 
We must set up automated reorder points based on actual consumption rates rather than static standing orders.
4. Audit the billing data to identify the specific "treatments causing losses". 
We must also analyze insurance claim denial codes to understand why payments are being withheld.   
5. Isolate the data on the inconclusive tests. Is it a specific machine? A specific technician? Or a specific type of test?  
6. Monitor KPIs weekly and run a monthly operational review with stakeholders

--- 

## Tools & Techniques 
- Microsoft Excel (Pivot Tables, Pivot Charts, Slicers)
- Data cleaning and transformation in Excel
- Dashboard layout and visualization best practices
- Basic descriptive analytics and KPI design
 
--- 

## Project Files (included) 
- `Dashboard.xlsx` - interactive dashboard file
- `/datasets/` - raw data files used for analysis ( XLSX)
- `Presentation.ppt` — boardroom slide deck 
- `README.md` — this documentation

--- 

## How to Run / View 
1. Open `Dashboard.xlsx` in Excel (desktop recommended)   
2. Enable content (if prompted) to allow Pivot Tables and slicers to work   
3. Use slicers to filter by Admission type, medical condition, Age group, Test result, Admission Month.   
4. Refer to `Presentation.ppt` for a summary of insights and recommended actions

--- 

## Contact 
Blessing Shantel Nochiri
Email: _blessingshantel01@gmail.com_   
LinkedIn: _www.linkedin.com/in/blessing-nochiri-09478bb0_
