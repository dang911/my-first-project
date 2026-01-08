# PROJECT PROPOSAL

## 1. Project Title
Human Resource Management

## 2. Problem Statement
Manual employee management is time-consuming and error-prone. This project provides a simple console application
to manage employees and departments, support salary calculation, and generate basic payroll reports.

## 3. Target Users
- HR staff
- Department manager 
- Admin user

## 4. Scope & Core Entities
### 4.1 Entities
- Employee 
  - FullTimeEmployee
  - PartTimeEmployee
  - InternEmployee 
- Department
- Attendance/WorkLog

### 4.2 Data Fields (Minimum)
- Employee: id, fullName, dob, phone, email, departmentId
- FullTime: baseSalary, bonus, allowance
- PartTime: hourlyRate, hoursWorked
- Department: id, name

## 5. Main Features 
### 5.1 Employee Management
- Add new employee (choose type: Full-time / Part-time / Intern)
- Update employee information
- Delete employee by id
- Display all employees
- Search employees (by name / by department)

### 5.2 Department Management
- Add / Update / Delete department
- Assign employee to department 

### 5.3 Payroll & Reports
- Calculate salary per employee 
- Total payroll of all employees
- Payroll by department

### 5.4 Data Persistence 
- Save and load data from file (CSV/TXT) in later milestones.

## 6. Expected Output
- A runnable .jar file.
- Source code with clear structure.
- Flowcharts and class diagrams.
- AI_LOG.md for AI usage documentation.
