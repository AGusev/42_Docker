#!/bin/bash
FROM debian

RUN	set -ex && apt-get update -y && apt-get upgrade -y && apt-get install nano -y && apt-get install git -y && apt-get install gcc -y

ENV 	NAME="agusev" && EMAIL="agusev@42.student.us.org" && MSG="Hello there"

RUN 	set -ex && echo $NAME >> hello.txt && echo $EMAIL >> hello.txt && echo $MSG >> hello.txt

