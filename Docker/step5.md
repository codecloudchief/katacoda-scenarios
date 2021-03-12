Step 5 - Binding Directories

So far, we've started containers and made them accessible by mounting ports. The next step is handling data.

Containers are designed to be stateless. Any data we want to be persisted after a container is stopped should be saved to the host machine. This is done by mounting/binding host directories into the container.

Binding directories (also known as volumes) in Docker is similar to binding ports using the option -v <host-dir>:<container-dir>. When a directory is mounted, the files which exist in that directory on the host can be accessed by the container and any data changed/written to the directory inside the container will be stored on the host. This allows you to upgrade or change containers without losing your data.
Task

The official Redis image stores logs and data into a /data directory. Start the container and mount the container's /data directory to the host /home/scrapbook/tutorial/data.
Protip

Docker allows you to use $PWD as a placeholder for the current directory. For example, the directory above could be replaced with "$PWD/data".

## Task
## Binding Directories

`docker run -d --name redisMapped -v "$PWD/data":/data redis`{{execute}}