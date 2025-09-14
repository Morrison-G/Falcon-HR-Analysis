# Falcon-HR-Analysis
> This Power BI work on Falcon HR case study aims to analysis total number of employees in the company, number of employees with the company, average age of employees in the company and job satisfactory rating of employees in the company. Key features are: Clean Data, and Visual charts to support business decision making.

> Case Study by Morrison (Analyst).

> ## Project Overview
> This case study analyses employees of falcon company, present age group of employees, job satisfaction ratings, total number of current employees.


> ## Tool Used
Power BI Desktop (Power BI Tool, visual charts).

> ## Data Cleaning Actions
Some data cleaning steps were applied to make the dataset proper for analysis without errors.

> ## Steps
### conditional columns: two conditional columns were created to aid result.
### measure column: one measure column was created to aid result.
### columns: removal of columns not needed.
### columns cleaning: trim and clean were used in some columns to aid result.
<img width="809" height="440" alt="image" src="https://github.com/user-attachments/assets/81216b2a-02ee-4d3f-9007-216d317ee96a" />
<img width="819" height="481" alt="image" src="https://github.com/user-attachments/assets/e5ff5476-1f51-462d-9df5-bd108590da56" />
<img width="819" height="478" alt="image" src="https://github.com/user-attachments/assets/196db61b-f408-487b-bbb9-d5d49382bf44" />
<img width="819" height="474" alt="image" src="https://github.com/user-attachments/assets/62616e1a-7c13-4451-b909-a459c981db49" />
<img width="819" height="473" alt="image" src="https://github.com/user-attachments/assets/9faa236f-dc4f-40a2-8d24-7134655fd5d7" />
<img width="809" height="465" alt="image" src="https://github.com/user-attachments/assets/d8d1ddbe-49f3-4d36-880d-30fae805aed1" />

> ## Key Business Questions Answered
1.	Total number of Employee that has worked with the company?

Create a card visual:

    - Value: Sum of employee count


2.	Total number of current Employee?

Create a card visual:

   - Value: Sum of current employee count


3.	Total number of Attrition?

Create a conditional column to get attrition count:

Create a card visual:

    - Value: Sum of attrition count


4.	Rate of attrition in percentage?

Create measure: Rate of attrition count 
= sum (HR data [attrition count]) / sum (HR data [employee count]).

Create a card visual:

    - Value: Sum of Rate of attrition count


5.	Average age of staffs in the company?

Create a card visual:

    - Value: Average of age count


6.	Attrition count grouped by department?

Create a pie chart visual:

- Axis: Department

    - Value: Attrition count


7.	Attrition count by Age group & gender?

Create a conditional column to get age sort: 
Sort cf – age band using age sort & arrange in ascending order.

Create a stacked column visual:

- x Axis: cf- age band
- y Axis: sum of attrition count
- legend: Gender


8.	Education field by attrition?

Create a cluster bar chart visual:

- x Axis: sum of attrition count
- y Axis: education field


9.	Using matrix to summarize job satisfactory rating?

Create a matrix visual:

- Rows: job role
- Columns: job satisfaction
- Value: Sum of attrition count


10.	Attrition count by age across department?

Create a stacked column visual:

- x Axis: age 
- y Axis: sum of attrition count
- legend: department


11.	Attrition rate by gender across different age group?

Create a donut chart visual:

- Legend: Gender
- Values: Sum of attrition count
- Details: cf - age band

Insert a card visual to show the total value, filter visual using cf – age band
- field: Sum of age count

> ## Findings
1.	The average age of staff working in the company is 37.
2.	R & D department has the highest attrition count.
3.	The male gender has the highest attrition by age group.
4.	15% of staffs has left the company when total employed staffs are compared with current staffs. 
5.	Life & sciences has the highest education field by attrition.

> ## Conclusion
Using Power BI to generate visuals for business ready insight from identifying, understanding and knowing impacts or decision that affects revenue, when explored correctly or incorrectly.

