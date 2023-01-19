# Dockerfile

# Script       : weirdnehal
# Author       : Nehal Ahmed
# Github       : https://github.com/weirdnehal
# Messenger    : https://m.me/nehal.ahmed6
# Email        : misterweird10@gmail.com
# Date         : 19-01-2023
# Main Language: Python

# Download and import main images

# Operating system
FROM debian:latest

# Author info
LABEL MAINTAINER="https://github.com/weirdnehal/"

# Working directory
WORKDIR /NEHAL-PRO/
# Add files 
ADD . /NEHAL-PRO

# Installing other packages
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install curl unzip wget -y
RUN apt-get install --no-install-recommends php -y
RUN apt-get clean

# Main command
CMD ["./NEHAL-PRO.py", "--no-update"]

## Wanna run it own? Try following commnads:

## "sudo docker build . -t weirdnehal/NEHAL-PRO:latest", "sudo docker run --rm -it weirdnehal/NEHAL-PRO:latest"

## "sudo docker pull weirdnehal/NEHAL-PRO", "sudo docker run --rm -it weirdnehal/NEHAL-PRO"
