### `Lab-03`

#### `1. Perform the following  DB operations using Cassandra.`

1. Create  a keyspace by name Employee

2. Create a column family by name 
Employee-Info with attributes 
Emp_Id Primary Key, Emp_Name, Designation, Date_of_Joining, Salary,Dept_Name

3. Insert the values into the table in
batch

3. Update Employee name and Department of Emp-Id 121

4. Sort the details of Employee
records based on salary

5. Alter the schema of the table
Employee_Info to add a column Projects which stores a set of Projects done by
the corresponding Employee.

6. Update the altered table to add
project names.

7. Create a TTL of 15 seconds to
display the values of Employees.





#### `2. Perform the following  DB operations using Cassandra.`

1. Create  a keyspace by name Library

2. Create a column family by name
Library-Info with attributes Stud_Id Primary Key, Counter_value of type Counter,
Stud_Name, Book-Name, Book-Id, 

3. Insert the values into the table in
batch

3. Display the details of the table created and increase the value of the
counter

4. Write a query to show that a
student with id 112 has taken a book “BDA” 2 times.

5. Export the created column to a csv
file

6. Import a given csv dataset from
local file system into Cassandra column family