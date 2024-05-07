FROM safeerahmad01/ubuntu-py-npm:v1
# FROM ubuntu:20.04

ENV WORKDIR /root/web/

# RUN apt-get update 
# && apt-get install -y npm  
#libjpeg-dev zlib1g-dev 
# python3 python3-pip
WORKDIR  $WORKDIR

ARG foulder=FullStack_Ecommerce_App

COPY $foulder $foulder

# RUN pip3 install  -r $foulder/backend/requirements.txt

# RUN cd $foulder/frontend && npm i && npm audit fix

#  --break-system-packages
# pyproject.toml-based

# sudo apt-get install libjpeg-dev zlib1g-dev

EXPOSE 3000
