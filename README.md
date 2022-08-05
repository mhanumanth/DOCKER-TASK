A demonstration of Docker to implement a simple 3 tier architecture

The front end uses ReactJS and built from a node:alpine image.
frontend will be able to access the mid-tier
mid-tier will be able to access the db MongoDB
In order to run this in docker, simply type docker-compose up at the command prompt. 
Docker will then create the MongoDB from the stock mongo image. 
The api uses nodejs with express and is built from a node:alpine image. 
![image](https://user-images.githubusercontent.com/110584678/183073992-f6ee3e3f-9460-45e2-bfa1-c66df8cb1957.png)
