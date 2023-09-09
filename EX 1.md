# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```sql
create table students(rollno int,name varchar(30),age int,address varchar(50),phoneno int);
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/I2_DBMS/assets/113497666/65fdf0a9-b7ac-4190-8ce2-f5fb10f57208)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table students add dept varchar(30);
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/I2_DBMS/assets/113497666/1336297f-75a7-4081-9a50-247db13ffe40)


### 3) Drop the student table
 
### SQL QUERY: 
```sql
drop table mystudents;
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/I2_DBMS/assets/113497666/6d90bad7-6c9d-47e4-bf3d-ab85f63deddc)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
truncate table mystudents;
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/I2_DBMS/assets/113497666/55d5ddd8-8bc1-47fc-af72-f0cf1e30ac35)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table students rename to mystudents;
```

### OUTPUT:
![image](https://github.com/Sachin-vlr/I2_DBMS/assets/113497666/8fc25d35-7a7c-44a7-8c2e-e6f9ad6bf85a)

## RESULT:
Therefore a student database is created and ddl commands are executed successfully. 
