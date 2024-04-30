FROM ubuntu

ENV WORKDIR /root/web/

RUN apt-get update && apt install -y python3 python3-pip git npm  libjpeg-dev zlib1g-dev

WORKDIR  $WORKDIR

ARG foulder=FullStack_Ecommerce_App

COPY $foulder $foulder

RUN pip3 install --break-system-packages -r $foulder/backend/requirements.txt 

# RUN cd $foulder/frontend
# RUN npm i

#  --break-system-packages
# pyproject.toml-based

# sudo apt-get install libjpeg-dev zlib1g-dev

EXPOSE 3000
