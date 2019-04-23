#!/bin/bash
FROM debian

RUN	set -ex \
	&& apt-get update -y \
	&& apt-get upgrade -y \
	&& apt-get install nano -y \
	&& apt-get install git -y \
	&& apt-get install gcc -y

# message
ENV 	NAME="agusev"
ENV 	EMAIL="agusev@42.student.us.org"
ENV 	MSG="Hello there"

# Add the data
RUN 	set -ex \
		&& echo $NAME >> hello.txt \
		&& echo $EMAIL >> hello.txt \
		&& echo $MSG >> hello.txt

# Start the container
CMD 	["bash"]
