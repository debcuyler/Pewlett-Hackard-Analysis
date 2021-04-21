# Pewlett Hackard Analysis
## Overview
Pewlett Hackard has a large number of employees that will be eligible to retire in the near future. Bobby and I have been tasked with creating a database to hold all of the employee and department data, along with titles and salaries. We have a new assignment to gather the following: The number of retiring employees by title, The employees eligible for the mentorship program and a written report summary

## Results
- Our first deliverable requested a list of employees whose birth date is between 1952 and 1955. This resulted in a csv with 133,776 employees. There are duplicates here as well as employees listed that no longer work for the company
- The second deliverable requested that the duplicate lines be removed from the first deliverable for employees who have had multiple titles in their career. Once this was complete, there were 90,398 employees in the file
- The third deliverable requested a count of all employees listed in the second deliverable by title. The breakdown by title is as follows:
	- Senior Engineer - 29,414
	- Senior Staff - 28,254
	- Engineer - 14,222
	- Staff - 12,243
	- Technique Leader - 4,502
	- Assistant Engineer - 1,761
	- Manager - 2
- The final deliverable requested a list of employees that are eligible for the mentorship program. These employees are current employees that were born in 1965. This resulted in a csv with 1,549 employees.
## Summary
- How many roles will need to be filled as the "silver tsunami" begins to make an impact? It is hard to know exactly by the queries that were requested and run. The query for the number of employees whose birth date is between 1952 and 1955 does not exclude employees that have already left the company. I would recreate the query to make sure that the list produced only contains current employees. When the query is re-run, it results in only 72,458 employees instead of 90,398.
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees? Based on the queries provided, there are only 1549 employees eligible for the mentorship program but approximately 72,458 employees due to retire in the very near future. Based on this, each mentor would need to train approximately 46 new employees. That would be on average of 12 new employees per year over a four year span. This seems excessive if an employee must train a new employee and do their own job. I believe they need to expand the mentorship program.
- I would also run a query by department for the mentorship program to see how many mentors would be available for each department and then also by title. This would give a better insight on the number of employees eligible. I would also expand out the birth date year to include additional employees. I also think that mentorship based on age may be deceiving as an older person may be brand new to the company and not well suited for the mentorship program. Perhaps it would be better to determine this group based on years of service (hire date) in order to better serve the program.
