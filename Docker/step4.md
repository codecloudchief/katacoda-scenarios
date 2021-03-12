Step 4 - Binding Ports

We've seen how to bind a port to a known port on the host. This makes it easier to access the service from other applications but has the disadvantage of only allowing a single instance of the service to be running. One of the advantages of running containers is that you can separate the application configuration (for example, which port to run on) from the deployment configuration (for example, which port to bind on the host).

Like binding a known port on the host, if you simply use -p 6379 to expose the port, then Docker will assign a random available port. This allows you to run multiple instances of the same service on the same host without changing any of the application configuration.

##Task

Start an instance of Redis as in the previous task but allow Docker to assign an available port.

You can use the command docker port redis 6379 to find out the mapped port.

Listing the containers using docker ps also displays the port mapping information.


##Binding Ports

`docker run -d --name redisDynamic -p 6379 redis:latest`{{execute}}

`docker port redisDynamic 6379`{{execute}}