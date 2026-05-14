# NYPD Arrest Analysis (Jan 2025) - Group 10

This is our final project for CIS 2300. We looked at NYC arrest data from the start of 2025 to see which boroughs have the most activity and what the demographics look like.

## 👥 The Team
* **Sarah Sellami** - Wrote the API code and handled the main notebook setup.
* **Valerie Grinberg** - Cleaned the data and renamed columns so they make sense.
* **Isaac Timmer** - Worked on the charts and the borough analysis.
* **Karla Jimenez** - Put together the final notes and project findings.

## 🚀 What we did
* **Getting Data:** We used the Socrata API to pull about 24,000 rows of data. We filtered it specifically for January 2025 using a `where` clause in Python.
* **Cleaning:** We used Pandas to fix the dates, rename messy API columns, and fill in missing values like "Unknown" genders.
* **New Columns:** We added two extra columns to help our analysis: `Day_of_Week` (to see if weekends are busier) and `Violent_Offense` (to separate serious crimes from smaller ones).
* **Charts:** We created bar charts and pie charts to show arrest trends by borough and age group.

## 🛠️ Tools Used
* Python (Pandas, Matplotlib)
* Socrata API (sodapy)
* .env file for API security
