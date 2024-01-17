# Registration-Login-Springboot-API

 'Registration-Login Spring Boot API'. This is a Spring Boot application that I designed to handle user registration, login, and authentication processes. I've included several HTML files  my application has a web interface for these functionalities. In my project, I have utilized various Java classes and configuration files which are typical for a Spring Boot application. I've specifically focused on using Spring Security for robust authentication and user management within the app.


 AppController.java: // Controller class managing web requests and responses.

Application.java: // Main class to bootstrap and launch the Spring Boot application.

CustomAuthenticationProvider.java: // Custom implementation for authentication logic.

CustomUserDetails.java: // Custom UserDetails class for storing user information.

CustomUserDetailsService.java: // Service to retrieve user details for authentication.

LoginRequest.java: // Data transfer object (DTO) for user login requests.

SecSecurityConfig.java: // Security configuration class for Spring Security.

User.java: // Entity class representing a user in the application.

UserRepository.java: // Interface for CRUD operations on User entities in the database.


-HTML- Using Thymeleaf

index.html: // The main landing page of the web application.

login_failure.html: // Page displayed on failed login attempts.

login_form.html: // HTML form for user login.

login_success.html: // Page displayed after successful login.

logout.html: // Page confirming successful logout.

register_success.html: // Page displayed after successful user registration.

signup_form.html: // HTML form for user registration.

users.html: // Page displaying list of users (likely for admin).

-Properties&POMfile-

application.properties: // Configuration file for application-wide settings.

pom.xml: // Maven configuration file with project dependencies.
