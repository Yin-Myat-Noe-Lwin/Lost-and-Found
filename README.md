# 🎓 Lost and Found - University Campus Platform

> A full-stack web application helping university students report, track, and recover lost or found items on campus.

[Java] [Spring Boot] [MySQL] [WebSocket] [JavaScript] [HTML5] [CSS3]

## Features

### For Users
- **Post Management**: Create, edit, and update lost/found item posts
- **Real-time Chat**: Communicate with other users about items using WebSocket
- **Media Sharing**: Send text messages, images, and videos in chats
- **Item Discovery**: Browse and search through lost/found listings

### For Admins
- **Post Moderation**: Review and approve user posts before public visibility
- **User Management**: Ban users who post inappropriate content
- **Platform Oversight**: Maintain community guidelines and platform integrity

## Tech Stack

### Backend
| Technology | Purpose |
|------------|---------|
| **Java Spring Boot** | REST APIs and business logic |
| **MySQL** | Relational database management |
| **WebSocket** | Real-time chat functionality |
| **JPA/Hibernate** | ORM and database operations |

### Frontend
| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure |
| **CSS3** | Styling and responsive design |
| **JavaScript (ES6+)** | Client-side interactivity |
| **SockJS & STOMP** | WebSocket client implementation |

## Prerequisites

Before you begin, ensure you have the following installed:

- Java JDK 11 or higher
- MySQL Server 8.0+
- Maven
- Git

## Installation

### Step 1: Clone the repository
```bash
git clone https://github.com/yourusername/lost-and-found.git
cd lost-and-found
```

### Step 2: Create database in MySQL
```bash
sql
CREATE DATABASE lost_and_found_db;
```

### Step 3: Import the SQL file

### Step 4: Build the project
```bash
mvn clean install
```

### Step 5: Run the application
```bash
mvn spring-boot:run
```

### Step 6: Access the application
```bash
http://localhost:8080
```
