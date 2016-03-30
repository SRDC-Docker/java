FROM srdc/ubuntu:14.04
MAINTAINER SRDC Ltd. <technical@srdc.com.tr>

#install openjdk 8
RUN \
  add-apt-repository ppa:openjdk-r/ppa && \
  apt-get update && \
  apt-get install -y openjdk-8-jdk && \
  update-alternatives --config java && \
  update-alternatives --config javac

# Define default command.
CMD ["bash"]