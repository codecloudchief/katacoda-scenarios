
## Step 3 - Listing Running Containers

As described in the introduction, each container is sandboxed from other containers. If a service needs to be accessible externally, then you need to expose a port to be mapped to the host. Once mapped, you will then be able to access the service as if the process was running on the host OS itself instead of in a container.

When starting the container, you define which ports you want to bind using the -p <host-port>:<container-port> option. The Redis container exposes the service on port 6379. If you wanted to map this port directly on the host, we'd use the option -p 6379:6379.

## Task

Start a new Redis container in the background with the name redis and bind the host port 6379 to the container port 6379.

## Protip

By default, the port on the host is mapped to 0.0.0.0, which means all IP addresses. You can specify a particular IP address when you define the port mapping, for example, -p 127.0.0.1:6379:6379


## Binding Ports

`docker run -d --name redisHostPort -p 6379:6379 redis:latest`{{execute}}
