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

run inventoryservice , bookingservice and orderservice

Access inventoryservice using API endpoint :http://localhost:8038/api/v1/inventory/event/1

<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/901fd890-b23f-400e-9bc6-812367b7435f" />





