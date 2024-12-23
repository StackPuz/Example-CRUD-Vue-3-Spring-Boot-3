# Example-CRUD-Vue-3-Spring-Boot-3
- The example shows how to Building a Vue CRUD App with a Spring Boot API and using MySQL as a database.
- The article of this repository https://blog.stackpuz.com/building-a-vue-crud-app-with-a-spring-boot-api
- To find more resources, please visit https://stackpuz.com

## Prerequisites
- Node.js
- JAVA 17
- Maven
- MySQL

## Installation
- Clone this repository `git clone https://github.com/stackpuz/Example-CRUD-Vue-3-Spring-Boot-3 .`
- Change directory to Vue project. `cd view`
- Install the Vue dependencies. `npm install`
- Create a new database and run [/database.sql](/database.sql) script to create tables and import data.
- Edit the database configuration in [/api/src/main/resources/application.properties](/api/src/main/resources/application.properties) file.

## Run project

- Run Vue project. `npm run dev`
- Run Spring Boot API project `mvn spring-boot:run`
- Navigate to http://localhost:5173