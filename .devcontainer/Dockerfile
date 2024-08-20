FROM python:3.10.4-slim-buster

RUN apt-get clean all && apt-get update
RUN apt-get install -y libsass-dev build-essential libcairo2 git libpango-1.0-0 libpangoft2-1.0-0 pangocairo-1.0 pngquant

COPY requirements.txt /build/requirements.txt
RUN pip3 install -r /build/requirements.txt
