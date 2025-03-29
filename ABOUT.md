# CMS with Angular and Microservices in NestJS

## General Description
This CMS is a modern and modular platform designed for web content management, supporting the creation of custom pages, microsites, and plugin integration. It is developed with **Angular** on the frontend and a **NestJS** microservices architecture on the backend, ensuring scalability and ease of maintenance.

## Technologies Used
- **Frontend:** Angular (with Angular Material and RxJS)
- **Backend:** NestJS with microservices
- **Database:** PostgreSQL / MongoDB / Redis
- **Authentication and Authorization:** JWT and RBAC roles
- **Real-Time Messaging:** WebSockets with Socket.IO
- **File Storage:**  Local with Nginx
- **Email Management:** Nodemailer with SMTP support
- **Infrastructure:** Docker

## Key Features

### 1. User and Role Management
- **Defined roles:**
  - **Administrator:** Full control over the system.
  - **Editor:** Can create and modify content.
  - **Designer:** Handles visual appearance.
  - **Reviewer:** Approves or rejects changes before publication.
- RBAC (Role-Based Access Control) permission management.

### 2. Page Creation and Management
- Content editor.
- Ability to add custom plugins (e.g., sliders, forms, widgets).

### 3. Microsites
- Creation of independent sites within the CMS with their own domain or subdomain.
- Customization with templates and themes.

### 4. File Upload and Management
- Support for images, documents, and multimedia files.
- Storage in local storage.

### 5. Email Sending
- SMTP support with providers like SendGrid, Mailgun, or Gmail.
- Automated emails for password recovery and MFA.

### 6. Real-Time Notifications
- Implementation with WebSockets for instant updates.
- Notifications for page changes, review requests, and review pages.

### 7. Plugin System
- Support for custom plugins to extend CMS functionalities.
- API for developers to create their own modules.
- Example plugins: dynamic forms, web analytics, third-party integrations.

### 8. Security and Authentication
- Authentication with JWT and Refresh Tokens.
- Protection against CSRF, XSS, and SQL Injection attacks.

### 9. API Gateway and Microservices
- Use of **API Gateway** with NestJS to manage microservice traffic.
- Separate microservices for:
  - **Authentication and authorization**
  - **Security management**
  - **CMS content**
  - **File storage**
  - **Email handling**
- Communication between microservices via RabbitMQ or Redis.

### 10. Administration and Dashboard
- Control panel with usage metrics and activity tracking.
- Interface customization and permission settings.

---
This CMS combines flexibility, scalability, and security, leveraging **Angular for a dynamic UI and NestJS with microservices for a robust backend**.

