CREATE DATABASE company;
USE company;

CREATE TABLE employees(
    -> id INT,
    -> name VARCHAR(50),
    -> age INT,
    -> department_id INT,
    -> salary DECIMAL(10,2)
    -> );

INSERT INTO employees VALUES
    -> (1,'john',25,101,30000),
    -> (2,'sarah',30,102,45000),
    -> (3,'mike',28,101,35000),
    -> (4,'emma',35,103,55000),
    -> (5,'david',26,102,32000);

SELECT * FROM employees;

SELECT * FROM employees WHERE salary > 30000;

UPDATE employees SET salary = 40000 WHERE id = 1;

DELETE FROM employees WHERE id = 2;

SELECT * FROM employees;

CREATE TABLE departments (
    -> department_id INT,
    -> department_name VARCHAR(50)
    -> );

SELECT * FROM departments;

INSERT INTO departments VALUES (101,'IT'), (102,'Hardware'),(103,'HR');

SELECT employees.name,departments.department_name FROM employees JOIN departments ON employees.department_id = departments.department_id;

SELECT AVG(salary) FROM employees;

SELECT COUNT(*) FROM employees;

SELECT department_id, AVG(salary)
    -> FROM employees
    -> GROUP BY department_id;


