# Hotel Management System

A scalable Hotel Management System built using Spring Boot, designed to manage hotel operations including room inventory, bookings, dynamic pricing, authentication, and payment processing.

## Features

### Authentication & Authorization

* JWT-based authentication
* Role-based access control
* Secure API endpoints using Spring Security

### Hotel Management

* Create and manage hotels
* Hotel profile and information management
* Hotel search and browsing

### Room & Inventory Management

* Room creation and management
* Inventory tracking
* Availability management

### Booking Management

* Create bookings
* Booking status tracking
* Guest management
* Booking history

### Dynamic Pricing Engine

* Base pricing strategy
* Occupancy-based pricing
* Holiday pricing
* Surge pricing
* Urgency pricing

### Payment Integration

* Stripe payment gateway integration
* Secure payment processing
* Webhook support

### API Features

* Global exception handling
* Standardized API responses
* DTO-based request/response architecture
* RESTful API design

## Tech Stack

### Backend

* Java 21
* Spring Boot
* Spring Security
* Spring Data JPA
* Hibernate

### Database

* PostgreSQL

### Build & Tools

* Maven
* Lombok
* ModelMapper

### Payment Gateway

* Stripe

## Project Structure

```text
src/main/java
├── advice
├── config
├── controller
├── dto
├── entity
├── exception
├── repository
├── security
├── service
└── strategy
```

## Getting Started

### Clone Repository

```bash
git clone https://github.com/rohitchourasia/hotel-management-system.git
cd hotel-management-system
```

### Configure Environment Variables

Create the following environment variables:

```text
JWT_SECRET_KEY=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret
STRIPE_WEBHOOK_SECRET=your_webhook_secret
```

### Configure Database

Update `application.properties` with your PostgreSQL credentials.

### Run Application

```bash
mvn spring-boot:run
```

or

```bash
./mvnw spring-boot:run
```

## Architecture Highlights

* Layered Architecture
* Strategy Design Pattern for Dynamic Pricing
* DTO Pattern
* Repository Pattern
* JWT Authentication
* Global Exception Handling
* RESTful API Design


## Author

Eshan Chourasia

* Java Backend Developer
* Spring Boot Enthusiast


---

If you found this project useful, consider giving it a star.
