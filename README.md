## Project Workflow for microservices

This is where all my confuguration and setup files are for my product-catalog microservices

# The Stack

1) Go programming language
2) MongoDB as database
3) gRPC, REST APIs
4) Docker and docker-compose for local orchestration
5) RabbitMQ
6) K8s
7) Nginx

# How to run locally

1) Clone this repositories
2) run docker compose up
3) Go to this link for the frontend https://products-frontend-green.vercel.app/
4) RabbitMQ for now it just push every newly created review to the queue and the broker consume it and log it out.