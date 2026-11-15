# 🎬 Movie Ticket Booking System

A **Java Console-Based Movie Ticket Booking System** developed to demonstrate practical application of Object-Oriented Programming (OOP), SOLID principles, and MVC (Model-View-Controller) architecture.

The application allows users to browse movies, explore theatres and available shows, select seats, book tickets, manage bookings, and view their booking history through an interactive console interface.

## 🚀 Features

### 👤 User Management
- User registration with personal details.
- User login and authentication.
- Manage user profile information.

### 🎥 Movie Management
- Browse available movies.
- View movie details.
- Explore movies currently available for booking.

### 🏢 Theatre & Show Management
- View available theatres.
- Browse movie shows by theatre.
- View show timings and ticket prices.
- Check seat availability for a particular show.

### 💺 Seat Management
- Display available and booked seats.
- Select seats for a movie show.
- Prevent booking of already reserved seats.

### 🎟️ Ticket Booking
- Book movie tickets.
- Generate booking details.
- Calculate the total ticket price.
- Manage booking status.

### 💳 Payment Management
- Process simulated ticket payments.
- Maintain payment details.
- Track payment status.

### 📋 Booking History
- View previous bookings.
- Access individual booking details.
- Track booking information.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Java | Core application development |
| OOP | Object-oriented design |
| SOLID Principles | Maintainable and extensible code |
| MVC Architecture | Separation of application responsibilities |
| Maven | Dependency and build management |
| JUnit 5 | Unit testing |

## 🏗️ Architecture

The application follows the **MVC (Model-View-Controller)** architectural pattern to separate business logic, user interaction, and application data.

```text
             USER
               |
               v
       +---------------+
       |     VIEW      |
       | Console UI    |
       +---------------+
               |
               v
       +---------------+
       |  CONTROLLER   |
       | User Actions  |
       +---------------+
               |
               v
       +---------------+
       |    SERVICE    |
       | Business Logic|
       +---------------+
               |
               v
       +---------------+
       |  REPOSITORY   |
       | Data Access   |
       +---------------+
               |
               v
       +---------------+
       |    MODEL      |
       | Domain Objects|
       +---------------+
```

### Design Principles

- **Encapsulation:** Protect object data using private fields and controlled access.
- **Abstraction:** Hide implementation details behind appropriate interfaces.
- **Inheritance:** Reuse common functionality where applicable.
- **Polymorphism:** Support flexible implementations through method overriding and interfaces.
- **Single Responsibility Principle (SRP):** Each class has a clearly defined responsibility.
- **Open/Closed Principle (OCP):** Design components to support extension without unnecessary modification.
- **Dependency Inversion Principle (DIP):** Depend on abstractions rather than concrete implementations.

## 📂 Project Structure

```text
MovieTicketBookingSystem/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/
│   │           └── movieticketbooking/
│   │               │
│   │               ├── model/
│   │               ├── view/
│   │               ├── controller/
│   │               ├── service/
│   │               ├── repository/
│   │               └── Main.java
│   │
│   └── test/
│       └── java/
│           └── ...
│
├── pom.xml
└── README.md
```

*Note: The structure above represents the logical organization of the application. Adjust package names and folders to match the actual repository.*

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- Java JDK 8 or later (depending on the configured project version).
- Apache Maven.
- Git.

### 1. Clone the Repository

```bash
git clone https://github.com/dineshpranavks/Ticket_booking_System.git
```

### 2. Navigate to the Project Directory

```bash
cd Ticket_booking_System
```

### 3. Build the Project

```bash
mvn clean install
```

### 4. Run the Application

Run the `Main.java` file from your IDE, or use the appropriate Maven execution configuration.

## 🧪 Running Tests

The project uses JUnit 5 for unit testing.

Execute the following command:

```bash
mvn test
```

## 🎯 Learning Objectives

This project was developed to gain practical experience in:

- Designing an application from functional requirements.
- Converting requirements into an Entity Relationship Diagram (ERD).
- Implementing real-world domain models using Java.
- Applying OOP concepts in a complete application.
- Understanding and implementing SOLID principles.
- Structuring applications using MVC architecture.
- Separating business logic from user interaction.
- Managing dependencies and building applications using Maven.
- Writing unit tests using JUnit 5.

## 🔮 Future Enhancements

- Integrate MySQL for persistent data storage.
- Implement password hashing and improved authentication.
- Introduce a real payment gateway.
- Add booking cancellation and refund functionality.
- Generate downloadable movie tickets.
- Develop a REST API using Spring Boot.
- Build a web-based frontend for the application.

## 👨‍💻 Author

**Dinesh Pranav K S**

- GitHub: [@dineshpranavks](https://github.com/dineshpranavks)
- LinkedIn: [Dinesh Pranav K S](https://www.linkedin.com/in/dineshpranavks/)

---

⭐ If you find this project useful, consider giving it a star!
