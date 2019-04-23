#!/bin/bash
From debian

RUN apt-get -y update && apt-get -y upgrade && apt-get install -y \
&&  wget http://dl.4players.de/ts/releases/3.0.13.8/teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2 \
&& tar xfvj teamspeak3-server_linux_amd64-3.0.13.8.tar.bz2

ENTRYPOINT ["sh", "teamspeak3-server_linux_amd64/ts3server_minimal_runscript.sh"]
