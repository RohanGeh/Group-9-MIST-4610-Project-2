# Group-9-MIST-4610-Project-2

# Team Members
Rohan Gehani [@RohanGeh](https://github.com/RohanGeh)

TJ Anderson: [@sta64960](https://github.com/sta64960)

Nick Forrester: [@NForrester02](https://github.com/NForrester02)

Zackary Williams : [@zackwilliams10](https://github.com/zackwilliams10)

Karan Sampath: [@ksampath0](https://github.com/ksampath0)

# Our dataset and What it contains

The data for this dataset was obtained in Montgomery County of Maryland
33 Columns, 172106 Rows

![d9d7e3b8ead84b1f965287ae4fd01672](https://github.com/RohanGeh/Group-9-MIST-4610-Project-2/assets/150191828/493dfa30-7449-4934-b203-40cb97b09aff)

# Our 2 Questions

The first question we chose for this project was “Are there seasonal patterns in driver substance abuse related to crashes?” This question is important because it may highlight certain tendencies for substance abuse-related vehicle incidents during certain holiday seasons or during certain warmer or colder periods. The question has implications for social and public health as being able to identify periods of heightened risk can potentially inform decisions on targeted interventions, increased safety measures, awareness campaigns, etc. Being able for law enforcement to be aware and plan accordingly for periods of increased substance abuse-related crashes could be a way to increase their efficiency as an organization. There is also an economic impact as substance abuse-related crashes can be extremely costly in medical expenses, property damage, legal costs, etc. Targeting seasonal patterns may be a way to increasingly allocate economic resources more efficiently towards certain seasons to try to alleviate some financial burdens. The question may also highlight certain social and cultural trends such as when are the periods of time where substance abuse is heightened, drinking patterns, and differences in driving behavior from season to season in the area that data is provided for. The data set has information on the amount of crashes where substance abuse was involved and the dates for each of these incidents by a police department in Maryland. With the data we can see the amount of incidents by seasonality to answer the question. 

The second question was “How do crash frequencies and severities vary by time of day?”. This question seeks to uncover any patterns and correlations between vehicular injuries and the time of the day. This question also has importance in safety and risk management as analyzing time of day crash information could be useful in informing strategies for improving road conditions and improving safety with programs that implement lighting and infrastructure changes. The question also could hold importance in policy-making, as road laws and regulations could be changed or implemented based on an analysis of the data. Workplace productivity can be directly affected by crashes occurring at certain times of the day and employers would have an interest in identifying peaks in crashes during work-times and investing in solutions. Being able to target patterns in crashes by time could lead to establishing technological and behavioral solutions to try to minimize injury and loss of life. Furthermore, being able to track higher severity of crashes to specific times of day can inform law enforcement and hospitals about when resources most need to be utilized. Different times of day may correlate with different driving behaviors, such as rush hour congestion, late-night fatigue, or reduced visibility during hours of dawn and dusk. Analyzing vehicle crash data across different time periods can provide insights into patterns. The data has information on vehicle damage extent along with the exact times for when crashes occurred. Looking at this data together can answer the question.

# Manuipulations
Question 1: In answering the first question we first narrowed down the Crash Date data to months in order to set the relationship of seasonality up within the visualization. We then used the Count measure on the Report Number data to count the number of incidents. We then implemented a filter to only include reports that indicated there was alcohol present, or alcohol was contributory.  Finally we filtered the Crash Date data within the visualization down to days using the details mark. This allowed the individual days to be marked on the Box and Whisker Plot.  

Question 2: In answering question two we needed to narrow the Crash Date data point down to hours in order to visualize the time of day of these occurrences. We also used the Count measure to count the number of crash reports in order to get the correct values. We then finally organized the visualization by Vehicle damage using the color Mark, which separated the count of incidents by the category of damage by color. 

# Analysis and Results
![image](https://github.com/RohanGeh/Group-9-MIST-4610-Project-2/assets/150191828/da8c1505-7c03-4028-8f02-3054d30e4f09)

Question 1: According to the box and whisker plot the number of alcohol substance abuse-related crashes was lower during the summer months and higher during the holidays. You can see a dip in the mean from the summer months of late June to September and gradually increase as the holiday season starts. Typically as the weather starts to get colder and people are inside more often alcohol consumption seems to increase. There are higher outliers in December and January related to Christmas and New Year’s. It’s safe to assume that as alcohol consumption increases so do alcohol-related accidents. 

![image](https://github.com/RohanGeh/Group-9-MIST-4610-Project-2/assets/150191828/ccc2fe43-5586-478a-abc6-83c940581107)

Question 2: Overall, throughout the day disabling, functional, and superficial damage was distinctly the highest amount of damage that was present. These numbers peaked at hours 16-18. This would be due to high volumes of people commuting back from work from 4 to 6 PM. The greatest amount of damage was disabling damage which is categorized as preventing the vehicle from driving off from the crash but was not completely destroyed. This seems to be the most significant amount of damage in crashes overall. Completely destroyed and no damage were relatively low throughout the day, almost being insignificant compared to the others.


# Tableau Packaged Workbook
[GroupProject2_SeasonalityPackaged (1).twbx.zip](https://github.com/RohanGeh/Group-9-MIST-4610-Project-2/files/15144068/GroupProject2_SeasonalityPackaged.1.twbx.zip)

# DataSet

[Crash_Reporting_-_Drivers_Data.csv.zip](https://github.com/RohanGeh/Group-9-MIST-4610-Project-2/files/15144069/Crash_Reporting_-_Drivers_Data.csv.zip)
