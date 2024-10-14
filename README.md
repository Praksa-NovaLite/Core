# Central Repository

This repository serves as a comprehensive hub for storing and organizing essential information, guidelines, and reusable components used across teams.

## Table of Contents

- [Overview](#overview)
- [Documentation](#documentation)
- [Infrastructure](#infrastructure)

## Overview

This repository is designed to streamline the access to critical resources for development, deployment, and maintenance of projects within the project. It promotes collaboration, consistency, and efficiency across teams by providing a centralized location for documentation and shared infrastructure components.

## Documentation

### Event Specifications
Concise overview of crucial event interfaces, defining data structures for seamless communication between system components. Developers can quickly reference this section for consistent integration in our event-driven architecture.

### ExamCreatedEvent
```json
{
    "$type": "ExamCreatedEvent",
    "examId": "{guid}",
    "candidateId": "{guid}",
    "questions": [
        "{guid}"
    ]
}
```

### [Coding Standards](docs/coding-standards.md)
Understand the coding conventions and practices that we follow to maintain clean, readable, and maintainable code.

## Infrastructure

### [RabbitMQ](inf/rabbitmq/README.md)
Discover the pivotal role of RabbitMQ in our system's communication strategy. This section provides insights into leveraging RabbitMQ as a dynamic message broker, fostering reliable and scalable interactions. Additionally, find Docker Compose files for quick and seamless integration within our distributed architecture.
