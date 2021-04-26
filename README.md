# MSSC Beer Service
This repo is for online course [Spring Boot Microservices with Spring Cloud](https://www.udemy.com/course/spring-boot-microservices-with-spring-cloud-beginner-to-guru/).

# Technologies
- Java 11
- Spring Framework, Spring Cloud    
    - Spring Cloud OpenFeign
    - Spring Cloud Config 
    - Spring Cloud Loadbalancer / Netflix Ribbon
    - Spring Security
- Project Lombok
- MapStruct
- Hibernate, MySQL, H2
- Apache Maven
- Apache ActiveMQ Artemis (JMS)
- Netflix Eureka
- Docker / DockerHub

# Default Port Mappings - For Single Host
| Service Name | Port | 
| --------| -----|
| Brewery Beer Service | 8080 |
| [Brewery Beer Order Service](https://github.com/RaggerBreak/mssc-beer-order-service) | 8081 |
| [Brewery Beer Inventory Service](https://github.com/RaggerBreak/mssc-beer-inventory-service) | 8082 |
| [Brewery Beer Inventory Failover Service](https://github.com/RaggerBreak/mssc-inventory-failover)  | 8083 | 
| [Brewery Configuration Service](https://github.com/RaggerBreak/mssc-config-server) | 8888 |
| [brewery Eureka Service](https://github.com/RaggerBreak/mssc-brewery-eureka) | 8761 | 
| [Brewery Gateway Service](https://github.com/RaggerBreak/mssc-brewery-gateway) | 9090 | 
