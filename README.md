# rbac
Role Based Access Control with spring security 


### Project Overview
- **Title**: Role-Based Access Control (RBAC) with Spring Boot and JWT.
- **Purpose**: Demonstrates implementing authentication and authorization for REST APIs using JWT with Spring Boot.
- **Key Features**:
  - **JWT Authentication**: Secure access to APIs using JSON Web Tokens.
  - **Role-Based Access Control (RBAC)**: Maps roles in JWT claims to Spring Security authorities.
  - **Login Endpoint**: `/login` endpoint issues JWT upon user authentication.
  - **SPA Compatibility**: Designed to work with Single Page Applications (SPAs) like ReactJS or Angular.

### Technologies Used
1. **Backend**:
   - **Spring Boot**: Provides the framework for building RESTful APIs.
   - **OAuth2 Resource Server**: Handles JWT authentication and RBAC.
   - **Java**: The primary programming language.
2. **Security**:
   - **JWT**: JSON Web Tokens for secure communication.
   - **Spring Security**: Implements authentication and access control.
   - **Keystore**: Stores cryptographic keys securely.

### Steps to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/IMS94/spring-boot-jwt-authorization.git
   cd spring-boot-jwt-authorization
   ```
2. **Build the Project**:
   Ensure you have **Java 8+** and **Maven** installed.
   ```bash
   mvn clean install
   ```
3. **Run the Application**:
   ```bash
   mvn spring-boot:run
   ```
4. **Access Endpoints**:
   - Use a REST client like Postman to test the `/login` and secured endpoints.

### Security Mechanisms
- **JWT Authentication**:
  - Ensures stateless authentication.
  - Tokens include user roles for RBAC.
- **Keystore Configuration**:
  - Securely stores private keys for signing JWT.

### How to Use
- Login via the `/login` endpoint to receive a JWT.
- Use the JWT as a Bearer token to access secured endpoints.
- Permissions are managed via roles in the JWT claim.

Let me know if you want the full README content or additional insights!
