# 🏨 AirBnb Booking Engine

A hotel booking platform built with Spring Boot featuring authentication, inventory management, dynamic pricing, and Stripe payment integration.

---

## 🚀 Features

- **JWT Authentication** – Secure login/signup with role-based access
- **Hotel Management** – CRUD operations for hotels and rooms
- **Inventory Tracking** – Real-time room availability
- **Booking System** – Create and cancel reservations
- **Payment Integration** – Stripe checkout for payments
- **Dynamic Pricing** – Smart pricing based on demand, holidays, and occupancy

---

## 🛠️ Tech Stack

- Java 17
- Spring Boot 3
- Spring Security + JWT
- Spring Data JPA
- PostgreSQL
- Stripe API
- Gradle

---

## 📦 Setup

```bash
# Clone repository
git clone https://github.com/Shatakshi-gupta-ggits/booking-engine.git
cd booking-engine

# Create PostgreSQL database
CREATE DATABASE booking_engine;

# Configure application.properties
# Edit src/main/resources/application.properties with your DB credentials

# Build and run
./gradlew clean build
./gradlew bootRun

Application starts at: http://localhost:8080

📁 Project Structure
src/main/java/com/aman/AirBnb/AirBnb/
├── Controller/     # REST API endpoints
├── Service/        # Business logic
├── Repository/     # Database operations
├── Entities/       # JPA entities
├── Dto/           # Data transfer objects
├── Security/      # JWT authentication
├── Strategy/      # Dynamic pricing strategies
└── Config/        # Configuration classes

🔑 Key API Endpoints
Method	Endpoint	Description
POST	/auth/signup	Register user
POST	/auth/login	Login user
GET	/hotels	Browse hotels
POST	/bookings	Create booking
POST	/checkout	Process payment
👥 Contributors
Aman – Backend Development

Shatakshi Gupta – Project Setup & Configuration

📄 License
MIT License
