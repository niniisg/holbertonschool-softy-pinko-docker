FROM ubuntu

RUN apt-get update

RUN apt-get upgrade -y

RUN apt-get install -y python3 python3-pip

RUN rm /usr/lib/python*/EXTERNALLY-MANAGED docker run -p 5252:5252 -it --rm --name softy-pinko-back-end-task3 softy-pinko-back-end:task3

RUN pip install flask

RUN pip install flask-cors

EXPOSE 5252

WORKDIR /app

COPY ./api.py /app/api.py

CMD python3 /app/api.py
