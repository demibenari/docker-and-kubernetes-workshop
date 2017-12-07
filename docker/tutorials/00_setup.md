## Setup

### Prerequisites
There are no specific skills needed for this tutorial beyond a basic comfort with the command line and using a text editor. Prior experience in developing web applications will be helpful but is not required. As you proceed further along the tutorial, we'll make use of [Docker Cloud](https://cloud.docker.com/).

### Setting up your computer
Getting all the tooling setup on your computer can be a daunting task, but getting Docker up and running on your favorite OS has become very easy.

The *getting started* guide on Docker has detailed instructions for setting up Docker on [Mac](https://docs.docker.com/docker-for-mac/), [Linux](https://docs.docker.com/engine/installation/linux/) and [Windows](https://docs.docker.com/docker-for-windows/).

*If you're using Docker for Windows* make sure you have [shared your drive](https://docs.docker.com/docker-for-windows/#shared-drives).

*Important note* If you're using an older version of Windows or MacOS you may need to use [Docker Machine](https://docs.docker.com/machine/overview/) instead.

*All commands work in either bash or Powershell on Windows*

Once you are done installing Docker, test your Docker installation by running the following:

#### Checking the Docker version
```
$ docker -v
Docker version 17.09.0-ce, build afdb6d4
```

#### Running the "Hello World" example
```
$ docker run hello-world
Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
ca4f61b1923c: Pull complete 
Digest: sha256:be0cd392e45be79ffeffa6b05338b98ebb16c87b255f48e297ec7f98e123905c
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://cloud.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/engine/userguide/
```

## Next Steps
For the next step in the tutorial, head over to [2.0 Webapps with Docker](./webapps.md)
