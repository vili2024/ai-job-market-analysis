# AI Job Market Analysis - 2000 Jobs | Excel Portfolio Project
**Author:** Thandiswa | Durban, SA | Excel Data Analyst
**Tools:** WPS Excel - PivotTables, Text-to-Columns
**Dataset:** 2001 rows

## LEVEL 1

### Q1 - Industry & Job Demand
- **Industry:** Automotive 300, Education 294, Retail 293 (Automotive highest)
- **Job Title:** Data Analyst 271 (most in demand)

### Q2 - Entry vs Mid vs Senior Salary
- Entry: $123,404 | Mid: $121,441 | Senior: $124,329
- Senior highest but Entry pays $1,963 MORE than Mid

### Q3 - Employment Type
- Internship: $124,213 (highest) | Full-time: $123,706 | Contract: $121,728

## LEVEL 2

### Q4 - Top 5 Skills
From your LEVEL 2 - TOP 5 list:
- TensorFlow 357, Pandas 349, Excel 331, GCP 326, Scikit-learn 324
- Method: Text-to-Columns on skills_required by comma, then count

### Q5 - Do Large companies pay more than Startups?
- Large: $124,356.07 - HIGHEST
- Startup: $122,606.45
- Mid: $122,185.58
- Grand Total: $123,040.00
**Answer:** Yes, Large pays $1,749 more than Startup (+1.4%)

### Q6 - Which industry pays highest for Data Scientists?
Filtered: job_title = Data Scientist
- Education: $130,636.54 - HIGHEST
- Healthcare: $126,682.61
- Tech: $126,597.13
- Automotive: $125,863.59
- Retail: $120,770.24
- Finance: $118,450.99
- E-commerce: $117,089.11
**Answer:** Education industry pays Data Scientists most.

### Q7 - Benefits package by job title?
**Status:** Column not present in provided dataset
- Verified columns: job_id, company_name, industry, job_title, skills_required, experience_level, employment_type, location, salary_range_usd, posted_date, company_size, Average_Salary
- No benefits column - analysis not possible on current file. Marked as N/A.

## LEVEL 3

### Q8 - Durban Roadmap to Mid-level Data Analyst
1. Excel + SQL + Python = $95k Entry
2. + Power BI = $108k
3. + Pandas = $118k Mid
4. + Scikit-learn = $125k
5. + AWS/GCP = $135k

### Q9 - Location premium?
- Remote: $122,150 average - 3% below Full-time but best for SA remote work (GMT+2)

### Q10 - FINAL RECOMMENDATION
**Data Analyst in Automotive = $144,393**
- Role with most jobs: Data Analyst (271)
- Industry with highest Entry DA pay: Automotive $144,393
- That's +11% above average Entry DA ($129,839)
- Skills: Excel (331 demand), SQL, Pandas, Power BI

## Files
- ai_job_market.csv
- Images
