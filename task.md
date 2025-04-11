# [Finals Lab Task 1 - Creating a Database using MySQL Workbench](https://github.com/user-attachments/files/19708478/GARCIA.-.LAB.TASK.1.-.FINALS.docx)
This portfolio focuses on learning the fundamentals of MySQL by working with a multi-level company database. It involves tasks such as writing SQL queries, designing table structures, and creating an EER diagram or relational schema. Additionally, it will include SQL scripts that define the database and tables to demonstrate how the database is constructed.

## Step by Step Process
### Step 1: Create the employees table
- Define employee_id as a unique integer, auto-increment, and primary key.
- Define employee_name as a VARCHAR (up to 255 characters), and make it not null.
- Define manager_id as an integer, which will be a foreign key referencing employee_id from the same table.
  
### Step 2: Create the departments table
- Define department_id as a unique integer, auto-increment, and primary key.
- Define department_name as a VARCHAR (up to 255 characters), and make it not null.
  
### Step 3: Create the employee_departments table
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define department_id as an integer, which will be a foreign key referencing department_id in the departments table.
- Set a composite primary key on the combination of employee_id and department_id.
  
### Step 4: Create the employee_projects table
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
- Define project_name as a VARCHAR (up to 255 characters), and make it not null.
  
### Step 5: Create the managers table
- Define manager_id as a unique integer, auto-increment, and primary key.
- Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.

## Query Statements
### Task 1
<img width="321" alt="Image" src="https://github.com/user-attachments/assets/ad398321-e9ed-44c4-9e6d-2470584f9fc6" />

### Task 2
<img width="308" alt="Image" src="https://github.com/user-attachments/assets/ff6eb8df-8811-473e-9baa-6508b314d5e3" />

### Task 3
<img width="342" alt="Image" src="https://github.com/user-attachments/assets/6a304718-cafc-4d4f-8b65-aaff2b0bc288" />

### Task 4
<img width="320" alt="Image" src="https://github.com/user-attachments/assets/52856c66-1270-4b29-a37e-dc0574726008" />

### Task 5
<img width="322" alt="Image" src="https://github.com/user-attachments/assets/d6872b16-2a75-43c3-a01a-3e321cc5409e" />

## Table Structures
### 1. Employee Table
![Image](https://github.com/user-attachments/assets/6c129109-9840-449f-809f-d896f03b5191)

### 2. Department Table
![Image](https://github.com/user-attachments/assets/4de56636-0640-4d1f-8f72-155b95e462d8)

### 3. Employee Department Table
![Image](https://github.com/user-attachments/assets/4de56636-0640-4d1f-8f72-155b95e462d8)

### 4. Employee Project Table
![Image](https://github.com/user-attachments/assets/f276f70f-b89e-45d2-90d3-500aa83781b9)

### 5. Manager Table
![Image](https://github.com/user-attachments/assets/8651397a-c3b2-425d-83ca-453214b92201)

## EER Diagram
![Image](https://github.com/user-attachments/assets/6f64c8c1-a6f6-488d-8dbe-fb3503041faa)



