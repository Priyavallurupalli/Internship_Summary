# Data Analyst Internship Summary

Welcome to my Data Analyst Internship project repository.  
During my internship, I worked on data cleaning, analysis, and visualization using Python, SQL, Excel, and Power BI.  

---

## Key Projects & Responsibilities

- Cleaned and transformed raw data to improve data quality and accuracy.  
- Developed SQL queries to extract and analyze data from databases.  
- Created interactive dashboards and reports in Power BI to support business decision-making.  
- Collaborated with teams to identify data trends and actionable insights.  

---

## Skills & Tools Used

- **Python** (pandas, numpy, matplotlib)  
- **SQL** (SELECT, JOIN, WHERE, GROUP BY)  
- **Power BI** for dashboard creation  
- **Excel** for data manipulation and reporting  

---

## Sample Code Snippets

### Python: Data Cleaning Example

```python
import pandas as pd

# Load sample data
data = pd.read_csv('sample_data.csv')

# Drop rows with missing values
cleaned_data = data.dropna()

# Convert column to datetime
cleaned_data['date'] = pd.to_datetime(cleaned_data['date'])

print(cleaned_data.head())
