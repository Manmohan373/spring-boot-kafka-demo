# Spring Boot Kafka Microservices Demo 🚀

This project demonstrates Apache Kafka integration using two Spring Boot microservices:
a **Producer** that publishes location updates and a **Consumer** that listens and processes those updates.

It showcases asynchronous communication between microservices using Kafka.

---

## 🧩 Microservices Overview

### 📦 1. deliveryboy – Kafka Producer
- Exposes a REST API to publish location updates.
- Uses `KafkaTemplate` to send messages to Kafka.
- Creates Kafka topic programmatically.

### 📥 2. enduser – Kafka Consumer
- Listens to the Kafka topic using `@KafkaListener`.
- Consumes and logs location updates.

Both services communicate via Kafka in a producer–consumer pattern.

---

## 🛠 Tech Stack
- Java 17
- Spring Boot
- Spring for Apache Kafka
- Apache Kafka
- Maven

---

👨‍💻 Author

Manmohan Pattnaik
Java | Spring Boot | Microservices | Kafka

## 🗂 Project Structure

