FROM python:3.6-slim

WORKDIR /app

ADD . /app

RUN apt-get update
RUN apt-get -y install git-core 
RUN pip install --trusted-host pypi.python.org -r requirements.txt

EXPOSE 80

CMD ["python", "black_out"]
