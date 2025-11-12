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

Write SQL query to add information:

insert into ticketing.venue(name,address,total_capacity)
value("Old Trafford","Manchester ,UK",80000),
("Ethihad Stuadium","Manchester ,UK",70000);

insert into ticketing.event(name,venue_id,total_capacity,left_capacity)
values("Coldplay",1,40000,40000),("Bruno Mars",2,30000,30000);



run inventoryservice , bookingservice and orderservice

Access inventoryservice using API endpoint :http://localhost:8038/api/v1/inventory/event/1, http://localhost:8038/api/v1/inventory/venue/1

<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/901fd890-b23f-400e-9bc6-812367b7435f" />


Access Booking service using API endpoint :http://localhost:8081/api/v1/booking

<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/d92f1fa7-1fe7-4731-83da-3b49faf2b62d" />




