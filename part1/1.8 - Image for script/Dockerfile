FROM ubuntu:18.04

WORKDIR /usr/src/app

COPY curler_commands.sh .

RUN chmod +x curler_commands.sh
RUN apt update
RUN apt install curl -y 

CMD ./curler_commands.sh