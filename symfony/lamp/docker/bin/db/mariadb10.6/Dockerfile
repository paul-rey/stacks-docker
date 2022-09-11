FROM mariadb:10.6

ARG USERNAME

RUN apt-get update \
 && apt-get install pv

WORKDIR /home/${USERNAME}/sql
