### Polls App
#### Create polls with ease
Create polls, get vote count with authentication system, which allows users to register and login
  
## Basic information regarding the application:

Purpose of the project
The purpose of the project was to develop a self-explanatory REST API Interface with an authentication system that would simplify the creation of polls and counting their votes. Because of REST architecture API is compatible with almost every modern front-end and mobile framework and can be used as Polling app or Polling Site, behavior similar to change.org, but instead of petition creation, an interface will allow the creation of polls.

## More information
If you want more information about API endpoints and their specification, please visit - Documentation If have postman desktop app, you can test all requests locally.

In this documentation, I will show the inside parts of the project step by step, explaining each part of the polling system. If you want to run a local version of the project you need to satisfy the following software requirements.

Originally the project was run and tested on IntelliJ IDEA, but if you don't want to use it there are other IDE's or you can run the project from the console.

Primary:

Java SDK 8 
Postgresql 11 or higher
Optional:

IntelliJ IDEA (For easier development and project start) - Comunity Version
# Configuration
After a successful installation configure the project to use your database and user, this can be done in application.properties file, change their properties to:

spring.datasource.url= jdbc:postgresql://localhost:5432/{your_db_name}
spring.datasource.username= {your_db_user}
spring.datasource.password= {db_user_pass}
# Deployment
The project is deployed on a free node of Heroku, but there is no use of visiting it because of token requirements no available browsable API in Spring Boot.


##### Note:
This repo contains Server Part written in Spring Boot

Detailed information about all endpoints and their specification can be found [here](https://documenter.getpostman.com/view/6754479/Szt8covo?version=latest#35a2fc61-8988-4c78-9ec3-7f779e53dee2),
documentation was created using Postman, if you have postman desktop app you can try all requests and test them out.
