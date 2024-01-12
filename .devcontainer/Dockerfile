FROM ghcr.io/shimamorieiki/devcontainer/python3_11_cabocha:latest

RUN apt-get update -y && apt-get upgrade -y

COPY requirements.txt requirements.txt
RUN pip install --upgrade pip && pip install -r requirements.txt

SHELL ["/bin/bash", "-c"]