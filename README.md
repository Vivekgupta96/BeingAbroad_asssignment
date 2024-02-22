# Institute Management System RESTful API

This project implements a RESTful API for an Institute Management System using Java and Spring Boot. It allows for the registration, modification, and retrieval of institute information. 


## Technical Requirements
- *Technology Stack:*
  - Java
  - Spring Boot
  - Database: MySQL


## Project Structure
- *The project follows a clean structure:*

  - src/main/java: Java source files
  - controllers: API endpoints
  - services: Business logic
  - repositories: Data access

## Functional Requirements

### Institute Registration

- *Endpoint:* /institutes/registration
- *Fields:*
  - Institute Name
  - Location
  - Contact Information
  - Additional Details

### Institute Modification

- *Endpoint:* PUT /institutes/{instituteId}
- *Fields:*
  - Institute Name
  - Location
  - Contact Information

### Institute Information Retrieval

- *Endpoint:* GET /institutes/{instituteId}

## Security and Registration Flow

1. *Institute Admin Registration:*
   - The POST /api/institutes endpoint allows Institute Admin registration without authentication.


## Define the command to run your application
CMD java -jar BeingAbroad-0.0.1-SNAPSHOT.jar


