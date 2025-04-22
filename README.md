This project implements **5 loosely coupled microservices**, designed for seamless communication and scalability. Event streaming is enabled between the **Order Service**, **Email Service**, and **Stock Service**, ensuring efficient and reliable data flow across services.

Key features of this project include:

- **Event-driven architecture** for asynchronous communication between services.
- Decoupled microservices to promote modular design and scalability.
- Built entirely using **Java**, leveraging its rich ecosystem for enterprise-level solutions.

---

### Microservices Overview

#### 1. **Order Service**
   - Handles creation, update, and management of orders.
   - Publishes events to notify other services (e.g., Email, Stock).

#### 2. **Stock Service**
   - Manages the inventory and updates stock levels based on order events.
   - Subscribes to events from the Order Service.

#### 3. **Email Service**
   - Sends email notifications (e.g., order confirmations, stock alerts).
   - Listens to events from the Order Service.

#### 4. **Payment Service**
   - Processes payments related to orders.
   - Ensures secure and reliable payment transactions.

#### 5. **User Service**
   - Manages user data and authentication.
   - Supports role-based access control.

---

###  Tech Stack

- **Language:** Java (100%)
- **Architecture:** Microservices
- **Event Streaming:** 
  - Designed with **event-driven principles** to enhance system reliability and scalability.
- **Communication:** 
  - Services communicate using **asynchronous messaging**.
