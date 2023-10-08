
First Commit was to Setting up project structure and creation of Dockerfiles for both the client and the backend.

Client Dockerfile: Defines the Dockerfile for the React frontend which includes copying source code and installing all dependencies.

Backend Dockerfile: Creating the Dockerfile for the Node.js backend, clearly outlining the source code and installing all the required Node modules.

Docker Compose file: Introducing a Docker Compose file at this stage to manage orchestration for the client and backend servicesrespectively.

Network Configuration: Configuring the network settings in Docker-Compose to ensure seamless communication between the client and backend containers.

Environment Variables: Adding environment variables in the Compose file to pass configuration values to the Node.js backend.

Database Container: Incorporation of MongoDB into the Docker Compose setup.

Linking the services: Setting up service linking in Docker-Compose to enable the client to communicate with the backend.

Building and Running: building and running the Docker containers for both client and backend.

Documentation in the README.md file 