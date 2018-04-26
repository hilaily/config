# MAINTAINER Laily <i@laily.net>
# Dockerizing Python: Dockerfile for building python env.

FROM python:2.7.10
MAINTAINER Laily <i@laily.net>

WORKDIR /usr/src/app

COPY pip.conf /root/.pip/pip.conf
COPY requirements.txt /usr/src/app/requirements.txt
RUN pip install -r /usr/src/app/requirements.txt

EXPOSE 8000

CMD ["bash"]
