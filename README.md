# DockerApacheProject
***
Simple docker project dockerizing an Apache web server

## 💻 Pre-requisites

Before you use this project you only need to have Docker installed in your computer.

https://www.docker.com/products/docker-desktop/

### Git clone
This will clone the project.
```
$ git clone https://github.com/Kar1stan/DockerApacheProject.git
$ cd DockerApacheProject
```

## 🚀 Run the Dockerfile: 
Open the terminal and run:
```
$ docker build -t my-apache-server .
$ docker run -it -p 1234:80 my-apache-server
```
