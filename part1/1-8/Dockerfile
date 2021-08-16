FROM ubuntu:18.04

COPY . .

RUN apt-get update
RUN apt-get install -qq -y curl
RUN chmod +x ./script.sh

CMD ./script.sh