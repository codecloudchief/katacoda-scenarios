In this first scenario, we'll explore how you can start and connect to your first container using Docker. The environment has been configured with the latest version of the Docker Engine and client which can be accessed via the command line.

The machine name Docker is running on is called docker. If you want to access any of the services, then use docker instead of localhost or 0.0.0.0.

## What Is Docker?

Docker describes themselves as "an open platform for developers and sysadmins to build, ship, and run distributed applications".

Docker allows you to run containers. A container is a sandboxed process running an application and its dependencies on the host operating system. The application inside the container considers itself to be the only process running on the machine while the machine can run multiple containers independently. As they're sandboxed, you avoid the possibility of conflicts between dependencies and simplify deployment as all installation and configuration are done ahead of time.

Docker has three key components. First is the Docker Engine, which provides a way to start containers on multiple different operating system platforms. Second is the Docker client, which allows you to communicate with the Engine. Third is the public Docker Registry that hosts Docker Images. These images can be launched or extended to match your requirements and application deployment.