# SIT722 Project Documentation

This repository contains the code for the SIT722 project, which consists of two microservices: **book_catalog** and **inventory_management**. Each service has its own Dockerfile.

## Directory Structure

- `book_catalog/`: Contains the code and Dockerfile for the book catalog service.
- `inventory_management/`: Contains the code and Dockerfile for the inventory management service.
- `docker-compose.yml`: The Docker Compose file to build and run the microservices.

## Building Docker Images

To build the Docker images for both services, follow these steps:

### Prerequisites

Ensure you have the following installed on your machine:

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Steps to Build Docker Images

1. **Open your terminal** and navigate to the project directory:

    ```bash
    cd "C:\Users\SRILAKSHMI V NAIR\OneDrive\Desktop\7.2P-resources (1)\project_part3"
    ```

2. **Run the Docker Compose build command** to build both Docker images:

    ```bash
    docker-compose build
    ```

    This command will read the `docker-compose.yml` file and build the Docker images for both the `book_catalog` and `inventory_management` services based on their respective Dockerfiles.

### Location of Dockerfiles

- The Dockerfile for the **book catalog** service is located in the `book_catalog` directory.
- The Dockerfile for the **inventory management** service is located in the `inventory_management` directory.

### Example Output

During the build process, you will see output indicating the progress. Look for messages like "Successfully built" and "Successfully tagged" to confirm that the images have been created successfully.

## Running the Microservices

To run the microservices, execute the following command:

```bash
docker-compose up
