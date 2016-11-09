#Cygni competence - 7 databases

This course is based on the book [Seven Databases in Seven Weeks](https://pragprog.com/book/rwdata/seven-databases-in-seven-weeks). However, Riak has been replaced with ElasticSearch. Apart from that, each chapter will be covered on the following occassions:

| Date       | Database        | Trainer               |
| ---------- | --------------- | --------------------- |
| 2016-11-17 | CouchDB         | Daniel Lenksjö        |
| 2016-12-12 | Neo4J           | Johannes Dolk         |
| 2017-01-26 | Redis           | Emil Bergström        |
| 2017-02-15 | PostgreSQL      | Rickard Lindström     |
| 2017-03-09 | MongoDB         | Fortunato Flores Ando |
| 2017-03-27 | HBase           | Pär Tjärnberg         |
| 2017-04-27 | ElasticSearch   | Henrik L. + Breding   |

## Course structure
For each occasion, we have prepared [docker images](https://hub.docker.com/r/cygni/7-databases/tags/) to reduce the time and effort needed to get database instances up and running. See the  `README.md` for each database for specific guidelines. Please make sure that you have read the chapter in the book as well as the 'Before we start' section in the `README.md` for the applicable database *before* the occasion. Also, please make sure that you have a docker installation that is working on your computer. Docker installtion instructions for different platforms follows below.

## Docker on Windows 10
On windows 10, you should install 'Docker for Windows'. This installation uses Hyper-V to run the Docker host.

- Instructions: https://docs.docker.com/docker-for-windows/
- Installer: https://download.docker.com/win/stable/InstallDocker.msi

## Docker on Windows 7 or 8
On Windows 7 or 8, you have to install 'Docker Toolbox'.

- Instructions: https://docs.docker.com/toolbox/toolbox_install_windows/ 

## Docker for Mac

- Instructions: https://docs.docker.com/docker-for-mac/

## Test docker
Make sure your docker installation works by running a simple 'hello-world' container:

``` bash
$ docker run hello-world
```

You should see the following output:

``` bash
Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker Hub account:
 https://hub.docker.com

For more examples and ideas, visit:
 https://docs.docker.com/engine/userguide/
```
