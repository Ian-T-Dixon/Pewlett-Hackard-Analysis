# Pewlett-Hackard Analysis
## Analysis Overview
Pewlett-Hackard is a large company with all of their data stored in Excel files. Our goal was to create a new database in SQL and move all of the data over.
Upon creation of the database, we used PGAdmin to query the new SQL database in order to gain insights into upcoming employee retirements in order to assist management
with planning the replacement of a large number of retirees. After seeing the large number of employees that may be retiring soon, management also asked us to create a list
of employees who could potentially shift to a part-time mentorship role to assist with onboarding new employees.

## Analysis Results
- There are over 36,000 departmental positions that will be getting ready to retire in the foreseeable future. Specifically the Development and Production departments will be hit the
hardest.
### Number of employees getting ready to retire by department.
![departments retiring](https://github.com/Ian-T-Dixon/Pewlett-Hackard-Analysis/blob/main/Data/department_retiring.PNG)


- With the largest proportion being Senior Engineers and Senior Staff.
### Number of specified retiring titles
![retirees by title](https://github.com/Ian-T-Dixon/Pewlett-Hackard-Analysis/blob/main/Data/title_count.PNG)
### Employees by unique title
![retirees](https://github.com/Ian-T-Dixon/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles.PNG)

- 
### Employees eligible for the mentorship program.
![mentorship eligibility](https://github.com/Ian-T-Dixon/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.PNG)

## Summary
Based on our analysis of the database we created, it is expected that there are 36,619 current employees that will be retiring over the next few years. This number is much
larger than the number of available candidates for the Mentorship Program. Using the desired parameters, each mentor would have to take on a substantial number of new
employees. This would indicate that management may need to broaden the requirements to be in the mentorship program, or scrap the idea all together.

![mentor count](https://github.com/Ian-T-Dixon/Pewlett-Hackard-Analysis/blob/main/Data/mentor_count.PNG)
