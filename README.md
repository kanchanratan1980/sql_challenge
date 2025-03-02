# # Employee Database Analysis Project  


##  Project Overview
This project creates an **employee database** for Pewlett Hackard using **PostgreSQL and pgAdmin**. It stores employee details, job titles, salaries, and department assignments.

---

## Setup Instructions (Using pgAdmin)**
### **1 Install PostgreSQL & pgAdmin**
- Download PostgreSQL and pgAdmin: [https://www.postgresql.org/download/](https://www.postgresql.org/download/)
- Open **pgAdmin** and connect to your PostgreSQL server.

### **2 Create the Database**
1. Open **pgAdmin**.
2. **Right-click on "Databases" → Select "Create" → Click "Database".**
3. Enter **`employee_db`** as the database name and click **Save**.

### **3 Create Tables**
1. Open **pgAdmin** and select **`employee_db`**.
2. Click on **"Query Tool"** (top menu).
3. **Copy and paste** the `module9.schema.sql` script.
4. Click **"Execute" (Play Button)**.
5. **It will create all six table  

### **4 Import CSV Data**
1. **Right-click on each table** → Select **"Import/Export"**.
2. Choose **"CSV"** format.
3. Click **"Browse"** → Select the corresponding CSV file.
4. Ensure **"Header"** is checked.
5. Click **"OK"** to import.
6. Repeat for all CSV files.

---

##  **Database Schema**
The database consists of six tables:

| Table | Description |
|--------|------------|
| `employees` | Stores employee details |
| `titles` | Stores job titles |
| `departments` | Stores department names |
| `dept_manager` | Tracks department managers |
| `dept_emp` | Links employees to departments |
| `salaries` | Tracks salary history |

---

## 📊 **Data Analysis Queries**
Run these modu9.query.sql **pgAdmin**.
## It will give you   
1*List all employees with their salaries**
2*employees hired in 1986  
3*list department managers    
4*list the employees with their department details  
5*employees with first name 'Hercules' and starting with 'B'   
6*Employees in Sales department  
7*employee in Sales and Development department  
8*count of last names in descending order   
## Project Summary
✔ Database Created .
✔ Tables Created & Data Imported 
✔ Data Queries Ready for Analysis 



