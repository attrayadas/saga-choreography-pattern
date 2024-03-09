# Microservices Architecture Patterns - SAGA Choreography Implementation

## Use case
When a user places an order, order will be fulfilled if the product's price is within the user's credit limit/balance. Otherwise, it will not be fulfilled. 

## Tech Stack
- Java 8
- Spring WebFlux
- Apache Kafka
- Spring Cloud Stream
- Multi-module project: Reuse component/classes

<img src="assets/saga pattern.png" alt="saga pattern diagram" style="width: 60%;">
