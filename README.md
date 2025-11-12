Microservices Booking System with Docker, Keycloak & SQL

A scalable microservices-based booking system built with Docker, Keycloak, and SQL, designed to demonstrate modern enterprise-grade architecture.
This project showcases how to integrate authentication, service orchestration, and data management in a containerized environment for a real-world booking platform (such as movie, travel, or event booking).

Tech Stack:
  Spring Boot
  Keycloak 
  MySQL
  Kafka
  Docker & Docker Compose
 API Gateway (Spring Cloud / NGINX) 

 Change MySQL Configuration to your username and password in all application.properties files 

 Setup Instructions
# Clone the repository
git clone https://github.com/Thirubalan7/ticketbookingproject.git
cd inventoryservice

# Build and start all services

docker-compose up -d

# Access Keycloak Admin Console
http://localhost:8080
# Default credentials: admin / admin

# Access Booking API Gateway
http://localhost:8081

