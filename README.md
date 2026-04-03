# 1. Tạo API Gateway (thường là HTTP)
nest g app api-gateway

# 2. Tạo Microservice (TCP, Redis, RabbitMQ, Kafka...)
nest g app user-service
nest g app order-service
nest g app notification-service

# 3. Tạo thư viện chung (rất quan trọng)
nest g library common
nest g library database
nest g library config