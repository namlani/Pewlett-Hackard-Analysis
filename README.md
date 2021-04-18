# Pewlett-Hackard-Analysis

## Overview of the Analysis

### Purpose
To determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Results
* The employee numbers, first name, last name, title, from_date and to_date are retrieved for employees who were born between 1952 and 1955:

  ![image](https://user-images.githubusercontent.com/5934390/115158361-c4411600-a05b-11eb-9bc2-4982e46c0ebb.png)

* Duplicate entries for employees that have switched titles over the years are removed, keeping only the most recent title of each employee:

  ![image](https://user-images.githubusercontent.com/5934390/115158427-0a967500-a05c-11eb-80ac-9ee6b14f1f59.png)
  
* The number of employees by their most recent job title who are about to retire are retrieved:

  ![image](https://user-images.githubusercontent.com/5934390/115158465-3ca7d700-a05c-11eb-9897-41de8d384c7f.png)
  
* A Mentorship Eligibility table that holds the employees who are eligible to participate in a mentorship program is created, retrieving data for current empoloyees who were born between January 1, 1965 and December 31, 1965:

  ![image](https://user-images.githubusercontent.com/5934390/115158540-a3c58b80-a05c-11eb-9906-0560fe5a22f4.png)
  
## Summary

### The following questions are answered from the analysis:
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?

  90, 398

* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

  No, there are only 1, 548 employees with mentorship eligibility.

### Additional analysis

* Broadening the criteria for mentorship eligibility to those born between January 1, 1962 and December 31, 1965 in order include more employees in the program would lead to many more qualified, retirement-ready employees who can mentor the next generation of Pewlett Hackard employees:

![image](https://user-images.githubusercontent.com/5934390/115158928-a75a1200-a05e-11eb-9d19-ec24d0c5222f.png)

* Querying for employee salaries based on title and employees who have been working at the company for less than a year can provide Pewlett Hackard with useful information when setting starting salaries for the next generation of employees
