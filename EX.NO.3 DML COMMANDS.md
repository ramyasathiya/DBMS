![314386206-8720bb8d-f4ca-41ef-b287-6fe267c30f09](https://github.com/ramyasathiya/DBMS/assets/119393543/f626f521-c9dd-4756-9c38-ea570b3ae224)![314383984-ba2b28e8-c07f-4bd2-92a5-c7f9ff5cbcbb](https://github.com/ramyasathiya/DBMS/assets/119393543/1fd7ca46-dd19-46e2-86a1-f42f7495c836)# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.

# THEORY
## DML(Data Manipulation Language)
*  The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements.
*  It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.

## List of DML commands: 
1. INSERT: It is used to insert data into a table.
2. UPDATE: It is used to update existing data within a table.
3. DELETE: It is used to delete records from a database table.
4. SELECT: The SELECT command shows the records of the specified table.

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![314383858-08b3adb1-4eaf-4f81-809f-85c2bbe09858](https://github.com/ramyasathiya/DBMS/assets/119393543/f2df86c4-553f-4fb9-acc9-5bd97944a659)


### OUTPUT:


![314383984-ba2b28e8-c07f-4bd2-92a5-c7f9ff5cbcbb](https://github.com/ramyasathiya/DBMS/assets/119393543/39d1173b-e3e7-4b9b-8057-ca65e2b60f4d)

### Q2) Delete the records from manager table where the salary less than 2750.


### QUERY:


![314384085-2d04b041-76d9-42c8-b53b-09bf9b84f790](https://github.com/ramyasathiya/DBMS/assets/119393543/05ea2c86-a288-4f10-a5fb-dc207710c9a2)


### OUTPUT:

![314384197-d457ebd6-dda6-4c5a-a815-0309fecffc7a](https://github.com/ramyasathiya/DBMS/assets/119393543/9bed1c38-9631-4aff-a931-a56008ac48c5)

### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)


### QUERY:

![314384331-d7a19291-a819-4924-a76b-50e57d0e60e5](https://github.com/ramyasathiya/DBMS/assets/119393543/68b82196-4fea-4109-a677-79a015a0f733)

### OUTPUT:


![314384445-e36c7577-284c-48b9-9f5a-ceb8a28b31ef](https://github.com/ramyasathiya/DBMS/assets/119393543/4965ca1c-24b1-416e-8778-b7cfb0396236)


### Q4)	List the names of Clerks from emp table.


### QUERY:

![314384588-c9d6cb7f-f046-468f-ba12-f07d5627656c](https://github.com/ramyasathiya/DBMS/assets/119393543/f0cdad2b-b996-42ae-8b16-bb43d52a87e3)

### OUTPUT:

![314384660-5690c103-3614-4b56-995c-8aa91fdf0632](https://github.com/ramyasathiya/DBMS/assets/119393543/cc5cc379-bdd7-41da-b049-67ea3aa9f99e)

### Q5)	List the names of employee who are not Managers.


### QUERY:

![314384769-ed2b8bc6-9744-4507-9efa-6ee619b0121a](https://github.com/ramyasathiya/DBMS/assets/119393543/b4824b71-cb7a-4c3f-a742-4ade6eaa9925)

### OUTPUT:


![314384886-ad292e85-71f6-4973-89e6-b552068d6238](https://github.com/ramyasathiya/DBMS/assets/119393543/1e3599fc-b8a8-4d4a-812c-14914bba1cf3)


### Q6)	List the names of employees not eligible for commission.


### QUERY:

![314384959-5fc05982-2582-4555-988e-68f98cfbedd5](https://github.com/ramyasathiya/DBMS/assets/119393543/1137f68d-944a-4c7b-92c2-6b499cdde63f)


### OUTPUT:
![314385053-17b71fea-e260-4aae-be9c-44f9af0f63bf](https://github.com/ramyasathiya/DBMS/assets/119393543/8e89b9bb-0b0b-4ace-8586-daaf224262d4)


### Q7)	List employees whose name either start or end with ‘s’.


### QUERY:
![314385153-16563f38-79bb-4d5e-85d1-c3d5b3337913](https://github.com/ramyasathiya/DBMS/assets/119393543/4447a6f1-f3d1-49eb-a6da-aa5eca1797ce)




### OUTPUT:

![314385253-1dc857c4-be2d-49af-9d8e-51033f6f6438](https://github.com/ramyasathiya/DBMS/assets/119393543/95adac34-891f-43ef-94ce-b429c248eb44)



### Q8) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:

![314385332-3b46d71d-8dc1-4ff5-945e-90edab99fd08](https://github.com/ramyasathiya/DBMS/assets/119393543/20b1c73b-fa1a-43ec-886a-65fe8c83a1fb)



### OUTPUT:

![314385466-8432ddde-ac46-44e8-b704-670b2007c15f](https://github.com/ramyasathiya/DBMS/assets/119393543/269392c2-5f1b-48bc-8598-24cd323ff1c0)

### Q9) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:

![314385559-09067236-5cb6-445d-a89a-e45e30b76c0c](https://github.com/ramyasathiya/DBMS/assets/119393543/1f08b561-9acc-4070-a453-64025b2b1c82)

### OUTPUT:

![314385633-ab5fa265-34fc-4c77-9dfd-e3877f58f825](https://github.com/ramyasathiya/DBMS/assets/119393543/5020b4e7-4a8c-4325-a846-e7fe2f065d4b)



### Q10)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:
![314385811-cda143f4-74ae-4505-8bf8-420e67dff1a9](https://github.com/ramyasathiya/DBMS/assets/119393543/78f3841a-0670-46ff-abb1-d5a8168e488e)



### OUTPUT:

![314385883-6d5bb7f4-88f4-4cc7-99ad-9f16adb6052a](https://github.com/ramyasathiya/DBMS/assets/119393543/8394d875-a8b6-44d4-b7f4-50a3e79a4eb7)

### Q11) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:

![314385967-5fe92e25-66c7-4041-a034-0e916ebc2145](https://github.com/ramyasathiya/DBMS/assets/119393543/6184f270-fd5f-4304-9f25-d0f6359ce83f)


### OUTPUT:

##![314386056-4be115c8-0a37-4565-8cc3-6b686cb5c809](https://github.com/ramyasathiya/DBMS/assets/119393543/51932179-ffbf-4f7e-a733-a8fdc49fbaca)
# Q12) Find number of rows in the table EMP

### QUERY:
![314386129-e08f0ffb-7473-4863-a3a7-d04dbf49002f](https://github.com/ramyasathiya/DBMS/assets/119393543/f7fd5ab6-c0f7-48a6-822e-fd123ee1f415)


### OUTPUT:

![314386206-8720bb8d-f4ca-41ef-b287-6fe267c30f09](https://github.com/ramyasathiya/DBMS/assets/119393543/d63a5f5c-1b08-4ba1-b841-fbbcbb0d36ef)




### Q13) Find maximum, minimum and average salary in EMP table.

### QUERY:
![314386323-26b1ef0f-e505-4446-86a8-42162134f9a9](https://github.com/ramyasathiya/DBMS/assets/119393543/514c2779-3d53-42bf-aa8f-328c315aa13d)






### OUTPUT:


![314386519-3b3eeb1f-6e58-4707-b15c-b9944f49dba6](https://github.com/ramyasathiya/DBMS/assets/119393543/d915496b-e4c6-4503-99e0-52b8a758add3)

### Q14) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:
![314386618-9733bf79-637d-41bc-926b-835580706972](https://github.com/ramyasathiya/DBMS/assets/119393543/edb1f5a4-96ff-4207-901c-d493b10b78fd)



### OUTPUT:


![314386700-06b2e7cb-0e01-4513-8490-e547e70c9ede](https://github.com/ramyasathiya/DBMS/assets/119393543/7ad6b9a4-738d-4a63-bc68-85391c429cb7)




## RESULT :
Thus the basic DML commands are executed.
