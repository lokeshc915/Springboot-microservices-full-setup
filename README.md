# Springboot-microservices-full-setup
End to End micro services with springboot kafka elastic search grafana prometheus
You can watch the tutorial on Youtube here - https://www.youtube.com/watch?v=mPPhcU7oWDU&t=20634s

How to run the application using Docker
Run mvn clean package -DskipTests to build the applications and create the docker image locally.
Run docker-compose up -d to start the applications.
How to run the application without Docker
Run mvn clean verify -DskipTests by going inside each folder to build the applications.
After that run mvn spring-boot:run by going inside each folder to start the applications.
