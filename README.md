# spring-boot-mongodb
Simple Application who run with docker mongodb container



Steps:

0. Clone this repository


##### Running the Mongo into a Docker container and application connect with container Mongo:

1. Run Docker Container with MongoDB
❯ docker pull mongo
❯ docker run --name mongodb -p 27017:27017 -d mongo
❯ docker ps
 Yeah your MongoDB is UP
 
2. Now you can run the Application and access localhost:8080 
 
 
That is it, automatically your application run with instance MongoDB Container.
 
