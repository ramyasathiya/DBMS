# EXP NO 1: ER DIAGRAM CREATION, RELATIONAL MODEL AND SCHEMA GENERATION  
### DATE
## AIM:
<div align="justify">
   To create a ER Diagram for Bank management system or College management system using ERD Plus tool and generate the relational model with schema. 
</div>

## Algorithm
1. Create a login with https://erdplus.com.
2. Create a new ER Diagram with name
3. Create a strong entity, relation and attributes.
4. Create a weak entity, relation and attributes.
5. Specify attributes unique, multivalued and composite attributes.

### ER Diagram 

![image (3)](https://github.com/ramyasathiya/DBMS/assets/119393543/1b13c7b8-e94d-4a18-8f29-a698e7ee05e3)


### Relational model

![image (5)](https://github.com/ramyasathiya/DBMS/assets/119393543/1d8d95d6-413a-4776-baba-640d977b2007)


### SQL DDL Schema 

```
CREATE TABLE Student
(
  Student_id INT NOT NULL,
  First_name INT NOT NULL,
  Last_name INT NOT NULL,
  DateOfBirth INT NOT NULL,
  Email INT NOT NULL,
  PhoneNumber INT NOT NULL,
  PRIMARY KEY (Student_id)
);

CREATE TABLE Program
(
  ProgramID INT NOT NULL,
  ProgramName INT NOT NULL,
  Department INT NOT NULL
);

CREATE TABLE Course
(
  CourseID INT NOT NULL,
  CourseName INT NOT NULL,
  Credits INT NOT NULL
);

CREATE TABLE Instructor
(
  InstructorID INT NOT NULL,
  First_Name INT NOT NULL,
  Last_Name INT NOT NULL,
  Email INT NOT NULL,
  Phone_Number INT NOT NULL
);

CREATE TABLE Enrollment
(
  EnrollmentID INT NOT NULL,
  StudentID INT NOT NULL,
  CourseID INT NOT NULL,
  Enrollment_Date INT NOT NULL
);
```
## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
