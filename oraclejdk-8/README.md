### Java Dockerfiles

Java Dockerfiles based on srdc/ubuntu (additional Java Cryptography Extension (JCE))

### Base Docker Image

* [srdc/ubuntu:16.04](https://hub.docker.com/r/srdc/ubuntu/)


### Installation
Execute either of the following:

    docker pull srdc/java:oraclejdk-8       [downloads the image from Docker Hub]
    docker build -t srdc/java:oraclejdk-8   [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/java:oraclejdk-8
