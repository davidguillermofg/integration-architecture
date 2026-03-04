# Integration Architecture

This repository contains the architectural diagrams for the **Integration Architecture** based on the **C4 Model**.

## C4 Diagrams

The following diagrams are included:

### 1. Context Diagram
Provides a high-level view of the system, showing how it interacts with external actors and systems.

File:
- `integrationarch-C4-Context.drawio.png`

### 2. Container Diagram
Shows the main containers (applications, services, databases, and cloud services) and how they interact within the system.

File:
- `integrationarch-C4-Container.drawio.png`

### 3. Component Diagram
Details the internal components within a container and their relationships.

File:
- `integrationarch-C4-Component.drawio.png`

## Technologies Used

The architecture is based on AWS cloud services and modern microservices patterns, including:

- Amazon EKS
- Amazon API Gateway
- Amazon RDS (PostgreSQL)
- Amazon EventBridge
- Amazon MSK (Kafka)
- AWS Lambda
- Amazon S3
- Amazon Cognito
- DynamoDB

## Purpose

These diagrams illustrate a **scalable, event-driven integration architecture** designed to support microservices, real-time processing, and hybrid integrations with legacy systems.
