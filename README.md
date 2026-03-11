# Delta Frontend

## Project Description

This is the frontend application for the DeltaSigma API project.
The frontend allows users to add a user and retrieve user details using the Spring Boot backend API.

The application is built using HTML and JavaScript and communicates with the backend using REST APIs.

---

## Live Application

Frontend (Vercel):
https://delta-frontend-eight.vercel.app

Backend API (Render):
https://delta-project-czl2.onrender.com

---

## How to Run the Project Locally

1. Clone the repository

git clone https://github.com/kumargirith71-cell/Delta-Frontend.git

2. Open the project folder

3. Open `index.html` in your browser

---

## Features

* Add a user
* Fetch user by ID
* Communicates with Spring Boot REST API

---

## API Endpoints Used

### Add User

POST
/delta/add

Example Request Body:

{
"id": 1,
"name": "John",
"email": "[john@gmail.com](mailto:john@gmail.com)",
"discription": "Test user"
}

---

### Get User By ID

GET
/delta/get/{id}

Example:

/delta/get/1

---

## Technologies Used

* HTML
* JavaScript (Fetch API)
* Spring Boot Backend
* REST API
* Vercel (Frontend Hosting)
* Render (Backend Hosting)

---

## Author

Girith Kumar
