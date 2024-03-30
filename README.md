# RUN THE COMMANDS BELOW TO BUILD AND EXECUTE YOUR CONTAINER.
````
$ docker build -t node-app:1.0 .
````
Builds our image
````
$ docker images
````
It lists available images
````
$ docker run -d -p 3000:3000 node-app:1
````
Bind the container port to the port you want it exposed in local host
````
$ docker ps
````
checks out for running services. Head to your browser and open localhost and your intended port.
