# GLOBAL-TERRORISM-ANALYSIS
### Overview
The Exploring Global Terrorism project is designed to analyze the patterns, causes, and impact of terrorism around the world. Using available data, this project aims to study global terrorism trends, including the frequency of attacks, the countries most affected, and the impact on human lives. The analysis will help identify patterns, common factors, and potential strategies for addressing terrorism on a global scale.

### Problem Statement
Terrorism is a widespread issue that disrupts societies and causes harm to individuals. Attacks can vary in scale and nature depending on the region and time period. Understanding the causes, frequency, and impact of terrorism is crucial to developing effective countermeasures and policies to prevent it.

### Objective
The primary objective of this project is to analyze global terrorism data, focusing on:

- Where and when terrorist attacks occur.
- Who is involved in these incidents.
- The severity and consequences of these attacks.
Through this analysis, we aim to gain a deeper understanding of global terrorism trends and provide insights that could be used to mitigate its effects.

### Dataset
The dataset used for this project contains the following columns:

- iso3c: Three-letter country code (ISO alpha-3).
- Country: Full name of the country.
- Rank: Rank of the country based on the severity of incidents.
- Score: Severity score for the country's terrorist incidents.
- Incidents: Total reported incidents in the year.
- Fatalities: Number of deaths caused by terrorist incidents.
- Injuries: Number of injuries caused by terrorist incidents.
- Hostages: Number of hostages taken during terrorist incidents.
- Year: Year the data was recorded.

### Key Findings 

During our analysis of global terrorism, we explored several key questions to gain insights into patterns and trends. The following questions summarize what we found:
1. Total Number of incidents took place in each Year
2. Total Incidents Taken place in each country
3. Top 5 countries with the largest decrease in incidents between 2012 and 2022
4. Top 10 countries with the highest number of incidents from 2012 to 2022
5. Identify the top 5 years with the highest total fatalities
6. Identify the top 10 Countries with the highest total fatalities
7. Display the number of occurrences of Rank 1 countries in the global terrorism dataset
8. Visualize the number of incidents in Iraq and Afghanistan from 2012 to 2022
9. Visualize the number of fatalities in Iraq and Afghanistan from 2012 to 2022
10. Visualize the correlation between different features such as Score, Incidents, Fatalities, Injuries, and Hostages in the dataset
11. The relationship between the number of incidents and fatalities in each country over the years

### Analysis and Visualizations
The project uses various Python libraries such as Pandas, Matplotlib, and Seaborn to analyze the dataset and generate insightful visualizations, including:
-Incident Analysis: Countries like Iraq and Afghanistan saw significant incidents and fatalities from 2012 to 2022, with a recent decreasing trend indicating potential improvement.
- Correlation Insights: The correlation matrix reveals a strong positive relationship between incidents, fatalities, and injuries, suggesting higher fatalities correlate with increased injuries
- Hostage Insights: Hostage incidents show less correlation with incidents, fatalities, and injuries compared to each other, indicating a unique dynamic in terrorism incidents.
- Cautious Interpretation: While strong correlations exist, they do not imply causation; other influencing factors may contribute to these relationships.
  
### Future Scope
- **Advanced Data Analytics:** Incorporate advanced data analytics techniques such as machine learning and predictive modeling to forecast future trends in terrorism based on GTI data.
- **Longitudinal Studies:** Conduct longitudinal studies to track changes in terrorism patterns over extended periods, providing deeper insights into evolving threats.
- **Comparative Analysis:** Expand the analysis to include comparative studies between regions or groups of countries to identify factors influencing terrorism differently across various contexts.

### How to Use
- Clone this repository to your local machine.
git clone https://github.com/your-username/exploring-global-terrorism.git
- Install the necessary Python libraries:
pip install -r requirements.txt
- Run the analysis scripts to explore the dataset and generate visualizations and insights:
python analysis_script.py
