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
## Best tools for monitoring
Prometheus:

Open-source.
Efficient metric collection and storage.
Easy service discovery for dynamic environments.
Built-in alerting and notification features.
Scalable architecture with federation.

Grafana:

Rich visualization options for monitoring data.
Dynamic and interactive dashboard creation.
Compatibility with various data sources.
Seamless integration with Prometheus for alerting and annotations.

Alert manager: 

Easy way of creating alerts 
predefined thresholds for creating alerts 

Node exporter:

To monitor health of linux servers
