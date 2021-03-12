
Certain containers, such as databases, are best run in the background. However, Docker is not limited to just running background services. Containers can run any application in the same way they would run on a regular host. Previously, we used the -d to execute the container in a detached, background, state. Without specifying this, the container would run in the foreground. If we wanted to interact with the container (for example, to access a command shell) instead of just seeing the output, we'd include the options -ti.

As well as defining whether the container runs in the background or foreground, certain images allow you to override the command used to launch the image. Being able to replace the default command makes it possible to have a single image that can be re-purposed in multiple ways. For example, the Ubuntu image can either run OS commands or run an interactive bash prompt using /bin/bash

## Example

The command `docker run ubuntu ps`{{execute}} launches an Ubuntu container and executes the command ps to view all the processes running in a container.

As we described at the start, from the container's point of view, the only process running is the one we launched.
