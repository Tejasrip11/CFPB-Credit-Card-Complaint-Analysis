# \# 2024 U.S. Credit Card Complaint Analysis

# 

# I explored credit card complaints published in the Consumer Financial Protection Bureau (CFPB) database to see which issues appeared most often, how complaint volume changed during 2024, and how companies responded.

# 

# \## Tools I used

# 

# \- \*\*Python, pandas, and Jupyter Notebook:\*\* checked and cleaned the data, then explored complaint patterns.

# \- \*\*Power BI:\*\* created the report visuals from the cleaned CSV.

# 

# \## What I did

# 

# I worked with 75,989 complaint records received in 2024. In Jupyter, I checked for missing values and duplicate complaint IDs. I found no duplicate complaint IDs. I filled 63 missing `sub\_issue` values and 213 missing `state` values with `Unknown`, then exported the cleaned data for Power BI.

# 

# My Power BI report shows the total number of complaints, the 10 most common issues, monthly complaint counts, and company response categories.

# 

# \## What I found

# 

# \- \*\*Problem with a purchase shown on your statement\*\* was the most common issue, with 14,595 complaints (19.21% of the records).

# \- Complaint volume was highest in \*\*August\*\* (7,355) and lowest in \*\*February\*\* (5,182).

# \- \*\*Closed with explanation\*\* was the most common company response category in the report.

# 

# \## Project files

# 

# \- `notebooks/credit\_card\_complaints\_analysis.ipynb` — Python cleaning and analysis

# \- `data/credit\_card\_complaints\_2024.csv` — original data extract

# \- `data/credit\_card\_complaints\_2024\_clean.csv` — cleaned data used in Power BI

# \- `CFPB\_Credit\_Card\_Complaints\_2024.pbix` — Power BI report

# 

# \## Data source

# 

The data comes from the \[CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/). I used a downloaded extract filtered to credit card complaints received in 2024. These counts describe published complaints; they do not represent all credit card customers or prove that a complaint was valid.

## Power BI report
===

# 

# !\[Credit card complaint dashboard](dashboard.png)

