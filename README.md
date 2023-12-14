# Dockerized Java Application with Nginx, MySQL, Memcached, and RabbitMQ

Welcome to this project! Here, a Java application smoothly runs on Tomcat, neatly packaged alongside Nginx, MySQL, Memcached, and RabbitMQ. The coordination is made easy with Docker Compose.

## Project Overview

- **Java Application**: The heart of the project, a Java application seamlessly integrated with Tomcat, wrapped in a Docker container for ultimate portability.
- **Web Server (Nginx)**: An Nginx container adeptly serving the Java application and doubling as a reverse proxy.
- **Database (MySQL)**: A Dockerized MySQL database dedicated to storing application data.
- **Caching (Memcached)**: Seamlessly integrate Memcached for efficient caching.
- **Message Queue (RabbitMQ)**: RabbitMQ provides robust messaging capabilities.

## Requirements

Ensure your system is equipped with Docker and Docker Compose.

- [Docker Installation Guide](https://docs.docker.com/get-docker/)
- [Docker Compose Installation Guide](https://docs.docker.com/compose/install/)

## Getting Started

1. **Clone the repository:**

     ```bash
     git clone https://github.com/yourusername/docker-java-app.git
   
2. Navigate to the project directory:
    ```
    cd docker-java-app
    ```
3. Launch the containers using Docker Compose:
   ```
   docker-compose up

   ```
   
Watch as the containers seamlessly build and launch based on the configurations in docker-compose.yml.

Access the Java application through your browser at http://localhost:8080





 




