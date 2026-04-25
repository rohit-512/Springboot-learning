# User Management API (Spring Boot)

## Features
- CRUD Operations
- Validation
- Global Exception Handling
- H2 Database Integration
- Search by Name (case-insensitive)
- Filter by Age / Age Range
- Pagination & Sorting

## Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- H2 Database

## APIs

### Create User
POST /user

### Get All Users
GET /users

### Search
GET /user/search?name=rohit

### Filter
GET /users/filter?minAge=20&maxAge=30

### Pagination + Sorting
GET /users/page?page=0&size=2&sortBy=name
