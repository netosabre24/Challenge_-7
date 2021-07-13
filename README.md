# Challenge 7 Pewlett-Hackard-Analysis

The goal of this project was to act as a Human Resources Analyst to determine who will be retiring in the next few years and how many positions and titles will Pewlett Hackard need to fill. By doing this I helped future-proof PH by generating a list of all employees eligible for the retirement package and a list of how many job titles are going to be open after that generation of employees retires.

 # Resources
* original Datasets
  * departments.csv
  * dept_emp.csv
  * dept_manager.csv
  * employees.csv
  * salaries.csv
  * titles.csv
 
 * Programs
   * PgAdmin
   * SQL
   * PostgresSQL
 
After reviewing the employee files for Pewlett Hackard, an entity relationship diagram was created using quick database diagrams to gather and organize the key elements from various data tables. The data was imported using postgres and the pgAdmin interface. SQL queries were written to create data tables by joining primary keys from different data sets together and establishing foreign keys. The leadership is concerned about a "silver tsunami," where there is a mass exodus of retiring employees creating a massive amount of job vacancies. SQL queries were created to generate a list of retiring employees by title and a list of employees eligible for mentorship.


In conclusion, it all depends on how many retiring employees are willing to stay and mentor others. Nevertheless, a good mentor to mentee ratio I would say is 1:3. That is one mentor for 3 new employees. Assuming each year there are more or less 13,000 employees retiring and 13,000 new employees entering, we would need 3,000-4,000 mentors distributed proportionally in all the departments. We would need that in order for every department to stay put, at least 25% of the retirees accept the mentorship program because that would leave PH witha a 1:3 ratio.
