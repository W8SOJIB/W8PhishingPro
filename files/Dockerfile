# Dockerfile

# Author       : KasRoudra
# Github       : https://github.com/W8SOJIB
# Messenger    : https://m.me/W8Vai
# Email        : w8sojib@gmail.com
# Date         : 12-01-2023
# Main Language: Python

# Download and import main images

# Operating system
FROM debian:latest
# Main package
FROM python:3

# Author info
LABEL MAINTAINER="https://github.com/W8SOJIB/W8PhishingPro"

# Working directory
WORKDIR PyPhisher/
# Add files 
ADD . /W8PhishingPro

# Installing other packages
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install php openssh-client -y
RUN pip3 install -r files/requirements.txt
RUN apt-get clean

# Main command
CMD ["python3", "W8PhishingPro.py", "--noupdate"]

## Wanna run it own? Try following commnads:
