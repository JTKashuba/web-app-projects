FROM python:3
MAINTAINER JT Kashuba "kashuba.jt@gmail.com"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
#CMD ["flask_minijax.py"]
