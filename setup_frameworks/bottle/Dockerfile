FROM debian

RUN apt-get -yqq update
RUN apt-get -yqq upgrade
WORKDIR .
COPY app.py .
RUN apt-get -yqq install python3 python3-pip 
RUN python3 -m pip install bottle
EXPOSE 5000
ENV NAME Hello
CMD ["python3","app.py"]

