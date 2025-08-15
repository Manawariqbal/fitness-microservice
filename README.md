# Fitness Microservices Project

## Overview
A distributed microservices architecture for managing fitness data and intelligent recommendations. This project includes:

- **eureka**: Service registry
- **userservice**: Handles user auth and profiles
- **activityservice**: Tracks and retrieves user fitness activities
- **aiservice**: Generates AI-based wellness or workout recommendations

## Tech Stack
- Java, Spring Boot
- Eureka for service discovery
- [Add your database, messaging, or other tools]

## Getting Started

### Requirements
- Java 11+
- Maven
- Docker (optional)

### Running Locally
1. Navigate to `eureka` folder and run:
   ```bash
   ./mvnw spring-boot:run
