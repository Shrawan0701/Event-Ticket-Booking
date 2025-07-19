# BookMyEvent – Event Ticket Booking Platform

##  Architecture

BookMyEvent is a **containerized** microservice-style backend system designed for managing events and tickets. It leverages **role-based access control** with **Keycloak** for authentication and authorization.

- The platform is built with **Spring Boot**, using **RESTful APIs** to support event creation, ticketing, and validation workflows.
- **Keycloak** handles secure login, registration, and admin/user role mapping.
- The entire app is **containerized using Docker** for easy deployment.


---

##  Features

- **Role-Based Authentication** using **Keycloak**
  - Admin: Create & manage events, monitor ticket scans
  - User: Book tickets, view their bookings
-  **Event Management**
  - Create and update events with details like date, location, capacity
-  **Ticket Booking**
  - Generate tickets for registered users
  - Each ticket contains a **QR Code**
-  **QR Code Scanning**
  - Validate tickets using unique identifiers
-  **Secured Endpoints** based on user roles

---

##  Tech Stack

### Backend
- **Java** – Programming Language
- **Spring Boot** – Microservice framework
- **Spring Security** – Endpoint protection
- **Keycloak** – Identity and Access Management
- **Docker** – Containerization
- **Maven** – Build and dependency tool

### Database
- **MySQL** – Relational database for persisting users, events, and tickets

---

## ⚙️ Running Locally with Docker

```bash
git clone https://github.com/Shrawan0701/Event-Ticket-Booking
cd Event-Ticket-Booking
docker-compose up

```

 ## Contact
Let's connect and discuss how this system can be extended or improved!

 Email: shrawanrw07@gmail.com

 LinkedIn: https://linkedin.com/in/shrawanwandhekar

