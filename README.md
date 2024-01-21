# Analyzing-students-mental-health-in-SQL 
Does going to university in a different country affect your mental health? A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.

The study found that international students have a higher risk of mental health difficulties than the general population, and that social connectedness (belonging to a social group) and acculturative stress (stress associated with joining a new culture) are predictive of depression.


Explore the `students` data using PostgreSQL to find out if you would come to a similar conclusion for international students and see if the length of stay is a contributing factor.

Here is a data description of the columns you may find helpful. 
| Field Name    | Description                                      |
| ------------- | ------------------------------------------------ |
| `inter_dom`     | Types of students (international or domestic)   |
| `japanese_cate` | Japanese language proficiency                    |
| `english_cate`  | English language proficiency                     |
| `academic`      | Current academic level (undergraduate or graduate) |
| `age`           | Current age of student                           |
| `stay`          | Current length of stay in years                  |
| `todep`         | Total score of depression (PHQ-9 test)           |
| `tosc`          | Total score of social connectedness (SCS test)   |
| `toas`          | Total score of acculturative stress (ASISS test) | 

Explore and analyze the students data to see how the study reached its conclusions and gain a better understanding of it. This project will take you through some exploratory analysis before investigating a specific factor for international students. The final query is the only part of your code that will be tested.

Your project will follow these exploratory steps:

Start by counting all of the records in the data, then all records per student type to see how the records are categorized and scored.
Filter the data to see how it differs between the student types.
Find the summary statistics of the diagnostic tests for all students using aggregate functions, rounding the test scores to two decimal places, remembering to use aliases.
Repeat this to summarize the data for international students only.
Your final query:

See if length of stay impacts the average diagnostic scores rounded to two decimal places for international students, and order the results by descending order of the length of stay.
The final output of your query with aliases will have a total nine observation rows and four columns: stay, average_phq, average_scs, and average_as, in that order.
