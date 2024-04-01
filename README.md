# Project Management Web Application

This is a simple web application for managing projects and tasks. Users can add new tasks, view existing tasks, and mark tasks as completed.

## Instructions

### Running Locally

1. Clone this repository to your local machine:
git clone <repository-url>

2. Navigate to the project directory:
cd project-management-web
3. Open the  file in your web browser.

### Running with Docker

1. Ensure Docker Desktop is installed and running on your system.

2. Build the Docker image using the provided Dockerfile:
docker build -t project-management-app 

3. Run a Docker container using the following command:
docker run -d -p 8080:80 project-management-app
4. Access the application in your web browser using .

## Assumptions and Decisions

- The application was designed to be lightweight and user-friendly, using HTML, CSS, and JavaScript to keep it simple and easily deployable.

- Docker was chosen for containerization to ensure portability and scalability across different environments. The Dockerfile provided encapsulates the application for easy deployment.

- The development process prioritized rapid prototyping and testing of core features to create a minimum viable product (MVP) for initial market testing.

  ## The link to the Docker Hub page
  https://hub.docker.com/repository/docker/kanisa1/web/tags?page=1&ordering=last_updated


