FROM ubuntu:22.04
WORKDIR /usr/src/app
COPY script.sh .
RUN chmod 744 ./script.sh
RUN apt update && apt install -y curl
CMD ./script.sh
