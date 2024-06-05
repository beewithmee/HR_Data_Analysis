# HR_Data_Analysis
Company's HR Data Analysis and Employee Attrition Analysis Dashboard

**Problem Statement**

The problem at hand revolves around comprehensively analyzing the phenomenon of employee attrition within Company ABC. Employee attrition, the process of employees voluntarily leaving the organization, poses significant challenges to organizational stability, productivity, and growth. By investigating the underlying causes, patterns, and implications of attrition, Company XYZ aims to develop strategic interventions to mitigate attrition rates and foster a more stable and thriving workforce environment.

**Data Preparation and Modelling**

After importing the data from the data source performed #powerquery is used for #datacleaning and #datamodelling. #dax are used to append or create calculated measures.

Data Size: 1473 rows, 38 columns

**Data Visualization**

Then an insightful dashboard is created that shows high-level overview of multiple parameters and KPIs. Different types of visualization methods like Line chart, Area chart, Bar chart, Column chart, Donut chart, Pie chart, Gauge chart are used.

**Observations**

The most significant number of attritted employees are from the lowest salary bracket which is 0k-5K.

Male Attrition% = 16.96% and Female Attrition% = 14.77%

The job positions that faced the highest attrition are Laboratory Technician, Sales Executive, Research Scientist and Sales Representative. 
Three of the mentioned job positions i.e. Laboratory Technician, Research Scientist, Sales Representative have average monthly incomes that lie in the lowest salary bracket.

Age groups of 18-25, 26-35, 36-45 of all five age groups faced highest attrition and all the mentioned have the lowest of average monthly income. 
In addition average monthly incomes of age groups 18-25 and 26-35 lie in the lowest salary bracket which is up to 5K.

A pattern from the data is found that shows an inverse proportional relation between salary hike percentage and attrition count. 
Employees having lowest percentage of salary hike has the highest contribution in attrition and employees having highest percentage of salary hike has least contribution in attrition.

An interesting pattern is seen that employees that previously worked with only one company have highest contribution in attrition i.e. approximately 41% followed by employees that have no experience or had not worked with any companies with a contribution approx. 10%. Then it settles down to 5%-7% with increase of experience in multiple number of companies. So almost 51% of attritted employees have experience with 1 or no companies. From the current employees in the company approx. 35% of employees have experience with only one company and approx. 13% of employees have not worked with any companies. So almost 48% of the employees belong to the highest contributing category in attrition in terms of experience.

**Final Verdicts**

Low salary of employees leads to attrition in significant numbers from different job roles and from different age groups.

Male Attrition% > Femal Attrition%

Low salary hike is one of the reasons for attrition.

Lack of experience or wish to gain experience from multiple companies can be a probable cause of attrition.
