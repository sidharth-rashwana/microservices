# microservices

**Description**

This project implements a microservices architecture to handle various functionalities including user registration and login, admin operations, AWS S3 operations, and product registrations. Each microservice is designed to perform a specific set of tasks, ensuring modularity, scalability, and maintainability of the system.

**Tech Stack**

Backend: FastAPI, Python, MongoDB, Docker, Redis, Kubernetes  

**Usage**

Each microservice within this project should be executed according to its specific description and guidelines. Please refer to the documentation provided for each microservice for detailed instructions on how to run them.

**Docker Usage**

To run the project using Docker, follow these steps:

1. Setup `.env` parameters

2. Ensure that Docker is installed on your system.

3. Open a terminal or command prompt.

4. Navigate to the project directory.

5. Run the following command:

    `sudo docker-compose build`  
    `sudo docker-compose -f docker-compose.yaml up`

This command will start the Docker containers specified in the `docker-compose.yaml` file, which may include the necessary dependencies and configurations for running the project.
