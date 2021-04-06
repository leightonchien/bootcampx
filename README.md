# BootcampX
Bootcamp X is a Lighthouse labs app that allows the staff to help students and mentors by offering quick insight into data like assignment completion and the effectiveness of assistance requests. In this exercise you can find the SQL queries to get data from the database.

##Entity Relationship Diagram (ERD)
!["entity_relation-diagram"]
(https://github.com/leightonchien/bootcampx/blob/master/docs/ERD.png)

##The Entities

###Main Entities
- students
- cohorts
- assignments
- assignment_submissions
- teachers
- assistance_requests

####Cohorts Attributes
- id: A unique identifier
- name: The name of the cohort
- start_date: The cohorts' start date
- end_date: The cohorts' end date

####Students Attributes
- id: A unique identifier
- name: The full name of the student
- email: The students' email address
- phone: The students' phone number
- github: The students' github profile url
- start_date: The students' start date of the Bootcamp
- end_date: The students' end date of the Bootcamp
- cohort_id: The id of the cohort that the student is enrolled in
