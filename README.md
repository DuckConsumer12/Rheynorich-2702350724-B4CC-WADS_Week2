# Github as a portfolio

- Name: Rheynorich
- ID: 2702350724
- Class: B4CC

# Topic: Microservices
![image](https://github.com/user-attachments/assets/a4b6eed3-e385-4222-81fa-40b07532acf8)

# What is Microservices in web dev?
Microservice is one out of 3 architechures for web development. Its architect is made out of a collection of small, independent services that communicate via APIs. Each one of the services has their own functions which makes the system scaleable, flexible and easier to maintain.

# Why do we use Microservices in web dev?
Scalability – Services can be scaled independently based on demand.
Flexibility – Developers can use different technologies for different services.
Faster Development & Deployment – Teams can work on separate services without affecting others.
Fault Isolation – If one service fails, the rest of the application keeps running.
Easier Maintenance & Updates – Updates can be made to a single service without redeploying the entire application.
Microservices are ideal for large, complex applications that need high availability and agility

# An example of Microservices in web dev.
![image](https://www.simform.com/wp-content/uploads/2023/12/Monolthic-vs.-Microservices-Architecture.png)

Microservices in ecommerce websites
Imagine you're building an e-commerce website using microservices instead of a monolithic architecture. Instead of one big system, you break it into separate, independent services:
1. User Service
- Manages user authentication, profiles, and account details.
- Uses JWT tokens or OAuth for security.
2. Product Service
- Handles product listings, descriptions, and prices.
- Uses a database like MongoDB or PostgreSQL.
3. Cart Service
- Manages shopping carts for users.
- Stores data in Redis for fast access.
4. Order Service
- Processes customer orders and payments.
- Connects to third-party payment gateways such as Stripe or PayPal.
5. Notification Service
- Sends emails, SMS, or push notifications about orders and promotions.
- Uses Kafka or RabbitMQ for event-driven messaging.
6. API Gateway (Optional)
- Acts as a single entry point for frontend requests.
- Routes API calls to the appropriate microservice.
- How They Communicate
- Services talk to each other using REST APIs, GraphQL, or gRPC.
- They use message brokers such as RabbitMQ or Kafka for asynchronous communication.
