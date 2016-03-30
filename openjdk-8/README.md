### Java Dockerfiles

Java Dockerfiles based on srdc/ubuntu

### Base Docker Image

* [srdc/ubuntu:14.04](https://hub.docker.com/r/srdc/ubuntu/)


### Installation
Execute either of the following:

    docker pull srdc/java:openjdk-8       [downloads the image from Docker Hub]
    docker build -t srdc/java:openjdk-8   [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/java:openjdk-8
