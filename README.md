# GO Learning - Microservices Web Application

<strong>Status:</strong> Learning ... <br />

This is the  repository for my learning course in Udemy.
- <strong>Course:</strong> [Working with Microservices in Go (Golang)](https://gameloft.udemy.com/course/working-with-microservices-in-go)
- <strong>Instructor:</strong> [Ph.D. Trevor Sawler](https://www.udemy.com/course/building-modern-web-applications-with-go/#instructor-1)

In this course, I built a Front End Web Application thats connect to 5 Microservices:
- <strong>Broker:</strong> optional single point of entry to micro services.
- <strong>Authentication</strong>: connects to Postgres.
- <strong>Logger</strong>: connects to MongoDB.
- <strong>Mail</strong>: sends email with a specific template.
- <strong>Listener</strong>: consumes messages in RabbitMQ and initiates a process.

Communication from between Microservices using:
- REST API with JSON as transport
- Sending & Receiving using RPC
- Sending & Receiving using gRPC
- Initiating and responding to events using Advanced Message Queuing Protocol (AMQP)