# kishori9-COVID-19-Health-Analysis
 utilized local data (survey), public data (behavioral data), and governmental data (IDPH, Cook County, CMS, and Census data) to uncover trends related to behavior, cases, deaths, and testing specific to COVID-19.
 Business Objectives:
We were curious to see:
• What are the various types of data available during a state-of-emergency like the COVID-19 global pandemic?
• What insights can we derive?
• Understanding the complexity of working with data during such a tumultuous time is important to get a sense of the type of data available.
• Get a better understanding of the types of databases that would be best suited for short-term
Emergencies.

User Requirements:
Users: Health data analyst, Health Insurance analyst’s and General public to understand the impact of Covid19.
User Requirements:
• To understand which ethnicity is highly affected.
• To understand what may be the highest medium (place like grocery, public malls etc.) to spread
the virus.
• Insightful information regarding testing results and deaths.

Business Rules:
• Business rule: We Only work on covid19 cases in Illinois State, Chicago City and Cook County.
Field constraint: Only Cook county of Chicago IL will be represented in Patient table
• Business rule: Every Patient must supply First name, last name, ethnicity & age.
Relationship constraint: The relationship between the tables must be governed by a participation
constraints wherein a record of information combination in the Patient table must be related to at least one record in the Covid19 impact table.
Data Details:
• Survey news is extracted from the information from individual survey form and general
news
• Covid medical information and nursing is limited to data world websites.
•Age group, census, contry_zip data is collected from public records for year 2020.
• All the social data is gathered from the public records and data world.

