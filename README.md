# Employee Management System

A full-stack web application to manage employees, departments, and project assignments.

---

## Technologies Used

- **Frontend**: Angular 17 + Bootstrap 5
- **Backend**: Spring Boot (Java)
- **Database**: 
  - MSSQL: `Employee`, `Project`, `Employee_Project` tables
  - MySQL: `Department` table

---

## Setup Instructions

### 1 Download the Project

```bash
git clone https://github.com/sasika2000dilshan-glitch/Employee-Management-System---C97123.git
cd employee-management-system
```

---

### 2 Backend Setup

#### Spring Boot (Department API)

```bash
cd departmentapi
```

Update `src/main/resources/application.properties` with your MySQL credentials.

Run the Spring Boot app:

```bash
./mvnw spring-boot:run
```

Access backend APIs:

- `http://localhost:8080/api/employees`
- `http://localhost:8080/api/departments`
- `http://localhost:8080/swagger-ui/index.html` *(if enabled)*

---

### 3 Frontend Setup

#### Angular App

```bash
cd employee-management-angular
npm install
ng serve
```

Open in browser:

```
http://localhost:4200
```

---

## Database Setup

### MSSQL – EmployeeDB

Run `employee_table_mssql.sql`, `project_table_mssql.sql`, and `employee_project_table_mssql.sql` in SQL Server.

### MySQL – departmentdb

Run `department_table_mysql.sql` in MySQL Workbench or CLI.

---

##  Routing

| Path           | Description                  |
|----------------|------------------------------|
| `/employees`   | Manage employee records      |
| `/departments` | Manage department records    |

---

## Developed By

Y A Sasika Dilshan  
BIT31303 – Full Stack Web App Assignment  
IMBS Green Campus – BIT04
