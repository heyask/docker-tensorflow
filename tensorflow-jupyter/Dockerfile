FROM tensorflow/tensorflow:latest-jupyter

RUN apt-get update -y
RUN apt-get upgrade -y
RUN apt-get autoremove -y

RUN pip install --upgrade pip
RUN pip install -U pandas
RUN pip install -U numpy
RUN pip install -U matplotlib
RUN pip install -U seaborn
RUN pip install -U sklearn
RUN pip install -U keras
RUN pip install -U graphviz
RUN pip install -U jupyterthemes
