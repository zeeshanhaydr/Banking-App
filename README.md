# Banking App API

A simple Banking Application built with Spring Boot, Java 17+, JPA, and MySQL. This project provides RESTful APIs to manage basic banking operations like creating accounts, making deposits and withdrawals, fetching account details, and deleting accounts.

## 🚀 Features

- Create a new bank account
- Deposit funds into an account
- Withdraw funds from an account
- Retrieve account details by ID
- View all accounts
- Delete an account

## 🛠️ Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- MySQL
- Lombok
- Postman (for API testing)

## ⚙️ Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/Banking-App.git

### 2. Set Up MySQL Database

Create a new database in MySQL:

CREATE DATABASE banking_app;

### 3. Configure application.properties

Set your MySQL username and password in:
src/main/resources/application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/banking_app  
spring.datasource.username=YOUR_USERNAME  
spring.datasource.password=YOUR_PASSWORD  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  

### 4. Run the Application

Use your IDE (like IntelliJ) or run via terminal:

./mvnw spring-boot:run

## 📫 API Endpoints

- POST /api/accounts — Create a new account  
- GET /api/accounts/{id} — Get account by ID  
- PUT /api/accounts/{id}/deposit — Deposit amount into account  
- PUT /api/accounts/{id}/withdraw — Withdraw amount from account  
- GET /api/accounts — Get all accounts  
- DELETE /api/accounts/{id} — Delete an account  

## 🧪 Testing the API

You can test the API using Postman or any REST client.

Example JSON body for deposit/withdraw:

{
  "amount": 100.0
}

## 📝 License

This project is open-source and available under the MIT License.

## 👤 Author

Zeeshan Haider  
GitHub: https://github.com/zeeshanhaydr
