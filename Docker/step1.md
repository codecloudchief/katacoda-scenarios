Step 1 - Running A Container

With Docker, all containers are started based on a Docker Image. These images contain everything required to launch the process; the host doesn't require any configuration or dependencies.

To start a container, you can either build your Docker image or, as in this scenario, use an existing image created by Docker and the community. Existing images can be found at registry.hub.docker.com/ or by using the command `docker search <image-name>`. For example, to find an image for Redis, an object-relational database system, you would use `docker search --filter=stars=3 redis`{{execute}}.

The --filter=stars=3 option indicates that only images with at least three stars should be displayed. People give projects they recommend a star rating on the Docker Registry. It's recommended you either go with the "Official" docker image which has been verified by Docker, or the one with the most stars.

## Task

To complete this step, launch a container in the background running an instance of Redis based on the official image.

After identifying the image name using search, you can launch it using `docker run <options> <image-name>`. By default, Docker will run a command in the foreground. To run in the background, you need to specify the option -d.

At this stage, you will not have a local copy of the image so that it will be downloaded from the Docker registry. If you launch a second container, the local image will be used.


## Protip

All containers are given a name and id for use in other Docker commands. You can set the friendly name by providing the option --name <new-name> when launching a container such as --name redis


## Running a container

`docker run -d redis:latest`{{execute}}