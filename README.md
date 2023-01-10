# nats-distributed-messaging
This is a simple project to highlight how nats is highly performant, scalable and easy to use as a messaging service.

## Setup NATS server
1. you can run it using docker-compose:
    
    ```docker compose up```  
   
   or directly with docker using 
   
   ```docker run -p 4222:4222 nats:2.7.0-alpine ```
2. alternatively you can download and install the right one for you system from https://docs.nats.io/running-a-nats-service/introduction/installation

## Running the publisher
1. install Golang
2. cd into publisher then run:
    ```go run main.go```


## Running the subscrider
1. install Node
2. cd into subscriber then run:

   ```npm install``` then  ```node index.js```
