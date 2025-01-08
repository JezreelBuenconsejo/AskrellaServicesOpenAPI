
# Askrella OpenAPI

This repository contains the OpenAPI documentation for Askrella services. It includes specifications for different services such as the Identity Service. which can be visualized using Swagger UI.

## Instructions

### Prerequisites

-   **Docker**: Ensure Docker is installed on your machine. You can download it from [Docker's official website](https://www.docker.com/).
    
-   **Docker Compose**: Docker Compose should also be installed, usually bundled with Docker Desktop.
    

### Steps to Set Up and Run

1.  Open a terminal and navigate to the root directory of this repository:
    
    ```
    cd /path/to/your/repository
    ```
    
2.  Ensure Docker Desktop is running.
    
3.  Start the Swagger UI container using Docker Compose:
    
    ```
    docker-compose up
    ```
    
4.  Open your browser and navigate to:
    
    ```
    http://localhost:5173/swagger/
    ```
    
5.  Test the endpoints by selecting the desired service from the dropdown menu.
    

## Additional Information

-   To get an Authorization token, visit the Askrella Dashboard Identity section at [https://dashboard.askrella.dev/identity](https://dashboard.askrella.dev/identity) (Debug Tab).
    
-   Currently, testing is limited to `localhost:5173` since it is the only URL included in the CORS policy that I can access
   