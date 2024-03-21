# Kafka Spring Boot Application

## Overview

This is a simpl kafka Spring Boot application integrated with Apache Kafka, aimed at demonstrating basic functionalities of producing and consuming messages using Kafka within a Spring Boot environment.

## Prerequisites

Before running this application, ensure you have the following installed:

- Java JDK 8 or later
- Apache Kafka (with Zookeeper)
- Apache Maven

[Continue to Setup](./setup.md)

# Setup

1. **Clone the Repository**:

2. **Build the Application**:

3. **Start Kafka and Zookeeper**:
Ensure Kafka and Zookeeper are up and running. If not, start them using the following commands:

4. **Create Kafka Topics**:
Create Kafka topics as per your configurations. You can use the following command:


5. **Update Application Configuration**:
Update `application.properties` with your Kafka configurations such as bootstrap server address and topic details.

[Continue to Running the Application]
 
 #Usage

- **Producer Endpoint**: 
  The application exposes a REST endpoint `/produce` to send messages to Kafka. You can send messages by making POST requests to this endpoint.

- **Consumer**: 
  The application also has a Kafka message listener configured to consume messages from the Kafka topic. You can observe the consumed messages in the console logs.

#Contact:----------------------------------------------------------------------------------------------------------
Developed by: [Natiraj_a Prajapati]
github: [https://github.com/natirajagithub]
