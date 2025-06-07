# Employee-Management
java-springboot backend for employee management


# 🧑‍💼 Employee Management System (Spring Boot + REST API)

This is a Spring Boot project that provides a RESTful API to manage employee data — including Create, Read, Update, and Delete operations. This backend supports frontend apps like React and can connect to MySQL or use H2 (in-memory) database.

## 🚀 Features

- Add new employees
- Fetch all employees
- Get employee by ID
- Update employee info
- Delete employee
- CORS enabled for React frontend at `http://localhost:3000/`

## 🛠 Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL / H2 Database
- Lombok
- REST API
- Maven

## 📁 Project Files Included

- `EmpController.java` — REST API controller
- `EmployeeEntity.java` — JPA entity
- `Employee.java` — DTO/model
- `EmployeeRepository.java` — JPA repository interface
- `EmployeeSerivce` and `EmployeeSerivceImpl` — service layer
- `EmProjectApplication.java` — main Spring Boot class
- `TestClass.java` — Java list test class

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/bcoder4702/Employee-Management.git
cd Employee-Management
