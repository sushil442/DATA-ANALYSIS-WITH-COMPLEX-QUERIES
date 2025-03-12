# DATA-ANALYSIS-WITH-COMPLEX-QUERIES
COMPANY: CODTECH IT SOLUTIONS
 
 NAME: SUSHIL SUBHASH PANDE
 
 INTERN ID: CT08VIC
 
 DOMAIN: SQL
 
DURATION:4 WEEKS

MENTOR: NEELA SANTOSH
This SQL script demonstrates various advanced data analysis techniques using a STUDENTS table. Here's a brief breakdown of the queries:

1. Creating the Students Table: • The students table is created with the following columns: o student_id (Primary Key) o name (Student Name) o score (Exam Score) o class (Subject/Exam Class) o exam_date (Date of the Exam)
2. Inserting Data: • Data for 7 students is inserted, each with a student_id, name, score, class, and exam date.
3. Advanced Data Analysis Queries: • Rank Students by Score in Each Class: o RANK() window function ranks students within each class based on their score in descending order. Tied students receive the same rank. • Subquery Example (Above Class Average): o This query uses a subquery to find students who scored above the average score in their respective class. • Common Table Expression (CTE) - Top 3 Students by Score in Each Class: o A CTE is used to rank students within each class, then select the top 3 ranked students in each class. • Window Function - Cumulative Score for Each Student: o The SUM() window function calculates the cumulative score for each student, ordered by exam date. • Subquery - Students Above Overall Average Score: o A subquery is used to find students who scored above the overall average score across all students. • CTE and Window Function - Students Above Class Average with Ranking: o A CTE calculates the class average score, and the RANK() function ranks students who scored above the class average, within their class. • Subquery - Best Scorer in Each Class: o A subquery identifies the highest score for each class, and then the main query finds the students with that score, i.e., the best scorer(s). Summary: • RANK() and SUM() window functions help in ranking students and calculating cumulative scores. • Subqueries find students who scored above averages, both for their class and overall. • Common Table Expressions (CTEs) simplify complex queries like selecting top scorers and filtering students based on averages.

OUTPUT 
![TASK2 1](https://github.com/user-attachments/assets/53f931bd-2731-4db3-9e40-82d954bb436b)

![TASK2 2](https://github.com/user-attachments/assets/0cb06a88-3c64-4dba-8a1a-ddceac3a72ae)

![TASK2 3](https://github.com/user-attachments/assets/26d7a26b-3083-4701-9861-c7e964f232cd)

![TASK2 5](https://github.com/user-attachments/assets/b465fd51-46df-4b35-8010-063121c96c6f)

![TASK2 6](https://github.com/user-attachments/assets/d0dbd24c-4d4c-4ff7-a107-f65ff5354e1f)

![TASK2 7](https://github.com/user-attachments/assets/cab4ecdc-504b-4eda-be7c-e800861bc3d4)

![TASK2 8](https://github.com/user-attachments/assets/e7600c8c-fe97-4d04-bc49-2a3ac2fef5d3)


