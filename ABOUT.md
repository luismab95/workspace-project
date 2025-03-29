# WORKSPACE with Angular Microfrontends with module federation and Microservices in NodeJS 

## General Description
This WORKSPACE is a modern and modular platform designed for web content management, supporting the creation of custom pages, microsites, and plugin integration. It is developed with **Angular** on the frontend and a **NodeJS** microservices architecture on the backend, ensuring scalability and ease of maintenance.

## Technologies Used
- **Frontend:** Angular (with Boostrap and Module federation for microfrontends)
- **Backend:** NodeJs with microservices
- **Database:** PostgreSQL
- **Authentication and Authorization:** JWT
- **Email Management:** Nodemailer with SMTP support
- **Infrastructure:** Docker

## Key Features

### 1. Integrate your microfrontends in mf-container
- **Microfrontends:**
  - **Authentication:** Pages for authentication.
  - **Security:** Pages to manage user information.
  - **Container:** Shell to integrate more microfronteds.

### 2. Email Sending
- SMTP support with providers like SendGrid, Mailgun, or Gmail.
- Automated emails for password recovery and MFA.

### 3. Security and Authentication
- Authentication with JWT and Refresh Tokens.
- Protection against CSRF, XSS, and SQL Injection attacks.

### 4. API Gateway and Microservices
- Use of **API Gateway**  manage microservice traffic.
- Separate microservices for:
  - **Authentication and authorization**
  - **Security management**
  - **Email handling**

---
This WORKSPACE combines flexibility, scalability, and security, leveraging **Angular for a dynamic UI apply module federation for microfrontends and NodeJS with microservices for a robust backend**.

