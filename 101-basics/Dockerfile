ARG OS=ubuntu
ARG OS_VER=23.10

FROM ${OS}:${OS_VER}

MAINTAINER Himanshu Bhandari

WORKDIR /app

RUN echo "Hello Docker!" > test.txt

## Build the above Dockerfile ##

  # docker build -f .\Dockerfile -t hdbhandari/101basic:latest .
  # docker run -it hdbhandari/101basic

# Will output:

  # root@bc2fbaa097bd:/app# cat test.txt
  # Hello Docker!