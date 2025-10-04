Scalable Event-Driven Chat System

A high-throughput, low-latency event-driven messaging system designed for real-time communication across distributed services.

FEATURES:
- Event-Driven Architecture: Utilizes Kafka for scalable, asynchronous message processing.
- Reliable Persistence: Messages are stored reliably in PostgreSQL using Prisma ORM.
- Real-Time Communication: WebSockets and Redis enable low-latency, bi-directional
communication.
- Fault Tolerance: Handles backpressure and ensures message durability.
- Scalable Design: Supports multiple services and high message throughput.

TECHNOLOGIES USED:
- Backend: Node.js, TypeScript
- Messaging: Apache Kafka, Redis
- Database: PostgreSQL, Prisma ORM
- Real-Time Communication: WebSockets (Socket.IO)
- Environment Management: dotenv

USAGE:
- Connect to the WebSocket server to send and receive messages in real time.
- Messages are published to Kafka, persisted in PostgreSQL, and broadcast via Redis for scalable
real-time updates.
