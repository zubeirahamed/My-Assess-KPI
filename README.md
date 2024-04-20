# My-Assess-KPI

## Dockerized a simple Hello world app using NestJs
### 1. Started with git clone https://github.com/nestjs/typescript-starter.git
### 2. Created a Dockerfile with instructions
### 3. Then, build the Docker image using the docker build command
docker build -t mynestapp .
### 4. Once the Docker image is build. Run the Container using docker run
docker run -d -p 3000:3000 mynestapp
-d runs the container in detached mode (background).
-p 3000:3000 maps the container's port 3000 to the host machine's port 3000 
we can access by ip
