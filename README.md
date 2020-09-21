## Simple server.

### Tools required
- Docker
- GO installation
- Your IDE

### Running application locally
- Change directory to project directory
- Build docker image with :
 `docker build -t simple-server:latest .`
- Run the image  with :
  `docker run -p 8080:8080 simple-server:latest`


Run the application, and hit http://localhost:8080 to make sure it is running
