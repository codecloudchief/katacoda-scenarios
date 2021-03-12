

While the launched container is running in the background, the `docker ps`{{execute}} command lists all running containers, the image used to start the container and uptime.

This command also displays the friendly name and ID that can be used to find out information about individual containers.

The command `docker inspect <friendly-name|container-id>` provides more details about a running container, such as IP address, volumes mounted and their locations and its current execution state.

The command `docker logs <friendly-name|container-id>` will display messages the container has written to standard error or standard out.
