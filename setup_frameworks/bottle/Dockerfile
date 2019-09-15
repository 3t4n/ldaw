FROM python:3
WORKDIR .
COPY app.py .
RUN pip install bottle
EXPOSE 5000
ENV NAME Hello
CMD ["python3","app.py"]
