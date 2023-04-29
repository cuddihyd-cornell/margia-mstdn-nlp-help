FROM python:3.10
USER root
RUN pip install requests
RUN mkdir /opt/app
WORKDIR /opt/app
COPY extract.py .
CMD [ "python3", "/opt/app/extract.py" ]
