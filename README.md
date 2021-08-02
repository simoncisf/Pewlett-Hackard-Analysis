# Pewlett-Hackard-Analysis
This project is a PostgreSQL analysis of Pewlett Hackard's employee database.

## Overview 
The objectives of this analysis are:
* Determining the number of retiring employees per title.
* Identifying the employees who are eligible to participate in a mentorship program.

## Results
* As seen in the image below, the oldest position is Senior Engineer, followed by Senior Staff and then Engineer.
* Only two managers are close to retiring.
* There are 1,940 employees eligible to give mentorship. 
* The number of employees eligible for mentorship are relatively few compared to the amount of employees about to retie. There is roughly 1 mentor for every 50 future vacancies. 

![retiring_by_title](/Users/simon/Desktop/retiring_by_title.png)

## Summary
The total number of upcoming vacancies is 90,398 which is an extraordinarily large nubmer of positions to fill. There are over 1,900 employees eligible to give mentorship, which means that there is roughly 1 mentor for every 50 vacancies, which is not nearly enough.

Using an additional query, we create a table called all_employees which gives us a total of 300,024 employees that work at PH. Based on this, we find out that almost a third of PH employees are about to retire, which is a siginificant amount. The silver tsunami is very much a real concern for PH and they should reorganize their staffing and maybe even their business units in order to account for this. One suggestion would be to make the eligibility requirements more lenient so that more employees are able to qualify to give mentorship to the new hires that are about to join the company.
