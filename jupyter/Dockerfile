FROM jupyter/tensorflow-notebook

USER root

RUN npm install -g tslab
RUN tslab install 

RUN apt update -y
RUN apt install graphviz -y


RUN python -m pip install torch
USER ${NB_UID}