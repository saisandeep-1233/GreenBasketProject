Grocery Application using React and Spring Boot

This project is a REST application built with React for the frontend and Spring Boot for the backend. It allows users to manage their accounts and ordered items.

=> Table of Contents

- Getting started
- Installation
- Running the application
- Usage
- Technologies used
- Contributing

Getting started:
- Node.js and npm installed.
- Java and Maven for Spring Boot.
- A compatible database (e.g., MySQL, PostgreSQL) with a schema created.

Installation:

- Clone the repository:
  git clone https://github.com/saisandeep-1233/GreenBasketProject.git

- Install frontend dependencies:
  npm install

- The same installation works for the admin part of the code.
  The admin code will be running at http://localhost:4200.

- Configure the backend:
  - Install Lombok.
  - Create a database named greenbasketdb1.
  - In the `application.properties` file, change the username and password for the database.
  - Import the MySQL dump data.
  - Run the project.
  - The backend server should now be running on `http://localhost:8080`.

- Start the React frontend:
  npm run dev
  The React development server should start and open the application in your default web browser at `http://localhost:3000`.

Access the grocery application through the web browser. Perform operations on the items.

=> Technologies Used:
  - React
  - Spring Boot
  - Java
  - MySQL

=> Contributing

Feel free to contribute to this project by opening issues or pull requests. Your contributions are welcome!
