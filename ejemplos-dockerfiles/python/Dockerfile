FROM python:2.7
MAINTAINER Richard Quinto (richardqa@gmail.com)
COPY . /app
WORKDIR /app
RUN echo "Hello world" >> hello
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
