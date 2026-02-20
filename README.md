# Bibflip API Platform

API REST for cubicle management application built with Java 17 and Spring Boot. 

[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.0-brightgreen.svg)](https://spring.io/projects/spring-boot)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-blue.svg)](https://www.postgresql.org/docs/17/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Architecture Patterns

### DDD (Domain-Driven Design)
- Bounded contexts
- Aggregates and entities
- Value objects
- Domain events

### CQRS (Command Query Responsibility Segregation)
- Separate write (commands) and read (queries) models
- CommandServiceImpl handles writes
- QueryServiceImpl handles reads

### Repository Pattern
- Abstract data access
- Interface in domain layer
- Implementation in infrastructure layer


## Links

- **Swagger UI**: [https://bibflip-api-platform.azurewebsites.net/swagger-ui/index.html](https://bibflip-api-platform.azurewebsites.net/swagger-ui/index.html)
