<h1>Grocery Application using React and Spring Boot</h1>

This project is a simple e-commerce application built with React for the frontend and Spring Boot for the backend. It allows you to manage a collection of items. GreenBasket is a comprehensive online platform designed to provide users with convenient access to a wide range of grocery products and supplies. Our goal is to empower individuals to manage their daily needs efficiently from the comfort of their homes.

=> Table of Contents

- Getting started
- Installation
- Running the application
- Usage
- Project Structure
- Technologies used

=> Getting started: 

- Node.js and npm installed. 
- Java and Maven for Spring Boot. 
- A compatible database (e.g., MySQL, PostgreSQL) with schema created.
  
=> Installation: 

-> Clone the repository: `git clone https://github.com/ProjectExcelr/Green-Basket.git`

-> Install frontend dependencies: ` npm install`

-> The same installation works for the admin part of the code.
       The admin code will be running at  `http://localhost:4200`.

-> Configure the backend: 

   Configure the database properties in application.properties.For example:
   ->MySQl properties:

   `spring.datasource.url=jdbc:mysql://localhost:3306/{your-db-name}?useSSL=false&serverTimezone=UTC` 

   `spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver`
   
   `spring.datasource.username={your username}`
   
   `spring.datasource.password={your password}` 

  - install lombok.
  - Import the my sql dump data and the run the project.
  - The backend server should now be running on `http://localhost:8080`.
  - Specify other configurations like server and logging as needed.

-> Build the spring boot project:

   `cd server mvn clean install`

-> Start the React frontend: `cd client npm run dev`
   
   The React development server should start and open the application in your default web browser at `http://localhost:3000`.

=> Usage

Access the E-commerce application through the web browser. Perform login, register, and all functions and check the changes in in database.

=> Project Structure

  -> The project is structured as follows:

   `admin`: This is the admin part of the react code.
   
   `frontend`: This is the user functionalities of the react code.
   
   `data`: This is the data of the products.
   
   `backend`:Contains the spring boot backend code.

=> Technologies Used:
  - React
   - Spring Boot
   - Java
   - MySQL


=> Contributing

   Feel free to contribute to this project by opening issues or pull requests. Your contributions are welcome!
