Student Management SQL Project

## Project Description
This project is a *Student Management System* using MySQL.  
It manages *students, courses, enrollments, and marks* and allows basic queries for analyzing student performance.

---

## Tables

1. *student*  
   - student_id (Primary Key)  
   - name  
   - age  
   - gender  

2. *course*  
   - course_id (Primary Key)  
   - course_name  
   - credits  

3. *enrollment*  
   - enrollment_id (Primary Key)  
   - student_id (Foreign Key → student.student_id)  
   - course_id (Foreign Key → course.course_id)  
   - enroll_date  

4. *marks*  
   - mark_id (Primary Key)  
   - student_id (Foreign Key → stud…
