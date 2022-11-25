# Pewlett_Hackard_Analysis
## Analysis
Analysis:
This analysis aims to help a big company called Pewlett Hackard, which boosts thousands of employees by generating a list of all employees eligible for the retirement package.  In the past, the company has been using Excel and VBA for their Data and work, but for the number of employees they are presented with, they have decided to update their methods to use SQL.
SQL consists of the following:

  •	Designing an ERD that will apply to the data.
  
  •	Creating and using a SQL database.
  
  •	Importing and exporting large CSV datasets into pgAdmin.
  
  •	Practicing using different joins to create new tables in pgAdmin.
  
  •	Writing essential- to intermediate-level SQL statements.
  
## Results:
## In the first deliverable, the query resulted in many duplicates due to having multiple positions.

![module 7 challenge](https://user-images.githubusercontent.com/114379268/204058608-f998acdd-9c50-47b5-a5b0-0d6eade63e19.png)
## And that’s why we used the DISTINCT ON statement to remove the duplicates and make the table more accurate, and we came up with the table presented below:![module 7 challenge 3](https://user-images.githubusercontent.com/114379268/204058739-0e0eda3c-510d-4922-8ec5-50e2a530541b.png)
## After using the SQL Database pgAdmin4, the results I came up with resulted in Retiring Counts by Title for a total of 90,398 potential retirees. The bulk of the retiring employees are "Senior Engineers" or "Senior Staff", indicating the departure of a significant portion of experiential knowledge. Recruiting will need to work very hard. 

![module 7 challenge 4](https://user-images.githubusercontent.com/114379268/204058839-10ee95d6-06eb-4c2d-a089-4b7b3307661a.png)
## There were 1549 employees born in 1965 in the Mentor Eligibility List
![module 7 challenge 5](https://user-images.githubusercontent.com/114379268/204058977-ef17c88b-0179-470a-8c31-a19b4960595d.png)

## Summary:

•	How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There will be many roles that need to be filled, approximately 90,398.

•	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Using the Mentor Eligibility List, there are 1549 employees born in 1965.  And about 90,000 retirees, the gap between these two numbers is significant.
