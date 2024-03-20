![Screenshot 2024-03-20 104326 dbms 3](https://github.com/ramyasathiya/DBMS/assets/119393543/86c05196-3016-4e58-9e0f-aac93bc60d82)# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:
### 1) Create a table student  and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

### SQL QUERY:
```
create table students(
    registernumber integer,
    name varchar(50),
    age integer,
    address varchar(60),
    phonenumber integer
    
);
```

### OUTPUT:
![Screenshot 2024-03-20 102844 dbms1](https://github.com/ramyasathiya/DBMS/assets/119393543/6a5760b3-6309-4ebd-87d1-504d4f2aa620)

### 2) Alter the above student table by adding another attribute department
### SQL QUERY: 
```
alter table students
add department char(80);
```


### OUTPUT:

![Screenshot 2024-03-20 102844 dbms1](https://github.com/ramyasathiya/DBMS/assets/119393543/0e9b603f-8344-4de9-b738-863d88e8391e)


### 3) Rename the student table to mystudent

### SQL QUERY: 
```
alter table students rename to mystudent;
```

### OUTPUT:
![Screenshot 2024-03-20 103616 dbms 2](https://github.com/ramyasathiya/DBMS/assets/119393543/79b7eddb-6bab-4143-885e-13752fb00b30)

### 4) Delete the mystudent rows using truncate keyword

### SQL QUERY: 
```
truncate table students
```

### OUTPUT:

![Screenshot 2024-03-20 104326 dbms 3](https://github.com/ramyasathiya/DBMS/assets/119393543/ecc06f75-ad8f-4b4a-bd83-32b56fea0a92)

### 5) Drop the mystudent table
 
### SQL QUERY: 
```
drop table students;
```

### OUTPUT:
![Screenshot 2024-03-20 104326 dbms 3](https://github.com/ramyasathiya/DBMS/assets/119393543/30d7c262-6b3f-41ab-b309-5a4760f8636c)







## Result:
         Thus the basic DDL commands in SQL are executed. 


