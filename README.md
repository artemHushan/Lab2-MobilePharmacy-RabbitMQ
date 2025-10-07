# Lab2: Mobile Pharmacy with RabbitMQ

## Overview
Professional microservices architecture implementation for mobile pharmacy system using RabbitMQ message broker.

## Architecture
- Clean Architecture with DDD principles
- Dependency Injection
- Repository Pattern
- Service Layer
- Domain Models
- CQRS approach

## Projects Structure
- MobilePharmacy.Domain - Domain models and interfaces
- MobilePharmacy.Infrastructure - Data access and RabbitMQ
- MobilePharmacy.Application - Business logic services
- MobilePharmacy.DrugService - Producer microservice
- MobilePharmacy.NotificationService - Consumer microservice

## Technologies
- .NET 8
- RabbitMQ
- Docker
- Serilog
- Microsoft.Extensions.*

## Quick Start
1. Clone repository
2. Run: docker-compose up -d
3. Run: dotnet run --project MobilePharmacy.NotificationService
4. Run: dotnet run --project MobilePharmacy.DrugService

## Features
- Drug expiry notifications
- Medication reminders
- Low stock alerts
- Professional logging
- Error handling
- Configuration management
