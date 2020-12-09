# Dockerfile to help explain concepts from my various Cisco Live Presentations:
#
# Michael Petrinovic 2019
# version 1.0
FROM python:3.6-alpine
LABEL maintainer_name="Pojchara Trainorapong"
LABEL maintainer_email="potraino@cisco.com"

RUN mkdir /app
ADD requirements.txt /app/requirements.txt
RUN pip install -r /app/requirements.txt
ADD hello.py /app/hello.py
RUN chmod +x /app/hello.py

CMD ["/app/hello.py"]
