# DBS311-Lab-6-Stored-Procedures-Iterative-Statements

Download Here: [DBS311 Lab 6 – Stored Procedures/Iterative Statements](https://codingherolab.com/product/dbs311-lab-6-stored-procedures-iterative-statements/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

1. Write a store procedure that gets an integer number n and calculates and displays its factorial.
Example:
0! = 1
2! = fact(2) = 2 * 1 = 1
3! = fact(3) = 3 * 2 * 1 = 6

. . .
n! = fact(n) = n * (n-1) * (n-2) * . . . * 1
2. The company wants to calculate the employees’ annual salary:
The first year of employment, the amount of salary is the base salary which is $10,000.
Every year after that, the salary increases by 5%.
Write a stored procedure named calculate_salary which gets an employee ID and for that
employee calculates the salary based on the number of years the employee has been working
in the company. (Use a loop construct to calculate the salary).
The procedure calculates and prints the salary.
Sample output:
First Name: first_name
Last Name: last_name
Salary: $9999,99
If the employee does not exists, the procedure displays a proper message.
3. Write a stored procedure named warehouses_report to print the warehouse ID, warehouse
name, and the city where the warehouse is located in the following format for all warehouses:
Warehouse ID:
Warehouse name:
City:
State:
If the value of state does not exist (null), display “no state”.
The value of warehouse ID ranges from 1 to 9.
You can use a loop to find and display the information of each warehouse inside the loop.
(Use a loop construct to answer this question. Do not use cursors.)
Example Submission
— ***********************
— Name: Your Name
— ID: #########
— Date: The current date
— Purpose: Lab 6 DBS311
— ***********************
— Question 1 – Copy of question from above
— Q1 SOLUTION –
CREATE OR REPLACE procedure_name(arg1 data_type, …) AS
BEGIN
….
DBS311 – Advanced Data Systems Summer 2020
3 | P a g e
EXCEPTION
WHEN OTHERS
THEN
DBMS_OUTPUT.PUT_LINE (Error!’);
END procedure_name;
— Question 2 – Copy of question from above
— Q2 Solution –
…
