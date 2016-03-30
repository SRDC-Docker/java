### Java Dockerfiles

Java Dockerfiles based on srdc/ubuntu

### Base Docker Image

* [srdc/ubuntu:14.04](https://hub.docker.com/r/srdc/ubuntu/)


### Docker Tags

* `latest` (default): Oracle JDK 8 (alias to `oraclejdk-8`)
* `oraclejdk-8`: Oracle JDK 8
* `openjdk-8`: OpenJDK 8

### Installation
Execute either of the following:

    docker pull srdc/java:tag       [downloads the image from Docker Hub]
    docker build -t srdc/java:tag   [builds from the local Dockerfile]


### Usage

    docker run -it --rm srdc/java:tag
