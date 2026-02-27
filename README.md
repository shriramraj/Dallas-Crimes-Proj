Crime Crushers

Comparative Crime Analysis of Dallas and Phoenix (2018 to 2022)

Overview

This project analyzes arrest and crime data from Dallas and Phoenix to identify patterns in criminal behavior, trends over time, and demographic relationships. The study was conducted using R and focuses on temporal trends, geographic distribution, weapon usage, age patterns, and felony charge disparities.

This work was completed as part of STAT 3355 Intro to Data Analysis.

Objectives
	•	Compare crime trends between Dallas and Phoenix
	•	Analyze whether holidays influence crime frequency
	•	Examine crime distribution across zip codes and precincts
	•	Study age patterns in criminal activity
	•	Evaluate weapon usage across different areas
	•	Investigate relationships between race, gender, and felony charges

Data Sources
	•	Dallas OpenData Crime Dataset (2018 to 2022)
	•	Phoenix OpenData Arrest Dataset (2018 to 2022)

Both datasets were cleaned and standardized to ensure comparability.

Methods
	•	Data cleaning using dplyr, stringr, and lubridate
	•	Date standardization and categorical normalization
	•	Aggregation and subsetting for balanced comparison
	•	Visualization using ggplot2
	•	Comparative statistical summaries across demographic and geographic variables

Key Findings
	•	Phoenix showed a steady decline in crime after 2020, while Dallas remained relatively stable.
	•	A major spike occurred in both cities on May 31, 2020, likely linked to nationwide protests.
	•	Holidays did not consistently increase crime rates.
	•	Low income zip codes showed higher crime and firearm usage.
	•	The 18 to 25 age group exhibited the highest crime frequency.
	•	Disparities in felony charges appeared across race and gender categories in Phoenix data.

Technologies Used
	•	R
	•	ggplot2
	•	dplyr
	•	tidyverse
	•	lubridate

Repository Structure
	•	Data cleaning scripts
	•	Visualization and trend analysis scripts
	•	Statistical summaries
	•	Final report documentation
