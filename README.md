# Pewlett Hackard_Analysis
 Employee database review with PostgreSQL

## Overview
The framework of this project was to examine the personnel rosters for a large corporation (Pewlett Hackard) with an eye towards soon-to-retire employees, and specifically how the Sales and Development teams would be effected.

![Entity Relationship Diagram](resources/EmployeeDB.png)

The starting input for the project were six CSV files. Their column headers and relationships are diagrammed in the ERD (Entity Relationship Diagram) shown above. Once relationships were mapped, databases were created, linked through keys, and the data from the CSVs were imported. Once this was done we were able to begin making queries and isolating useful chunks of information. These query results were then, in turn, exported into their own discrete CSV files for later review.

Early stage inquiries involved collecting lists of PH employees who where were "of retirement age," department managers, and potential retirees from select departments. The end-of-project Challenge section focused on creating two primary query results:
- a summary of the number of retiring employees by their current job title;
- a list of all employees eligible for a mentorship program designed for retiring staff.

## Results
The queries constructed in this project indicated that there truly is a "silver tsunami" coming down the pipes for Pewlett Hackard.
- 90,398 employees are about to retire from the company.
- The bulk of the retiring employees are "Senior Engineers" (33%) or "Senior Staff" (31%), indicating the departure of a significant portion of experiential knowledge. Recruiting will need to work hard to counter this brain-drain.
- Fortunately only two managers are retiring, minimizing need to train new leadership.
- The number of employees eligible for the mentorship program are few (1549) in comparison to the number of employees retiring.

## Summary
Overall this project was more geared towards information retrieval rather than proper analysis, but 
