FROM python:3-slim
WORKDIR /app
ADD requirements.txt /app/requirements.txt
RUN pip3 install -r requirements.txt
ADD . /app
EXPOSE 80

CMD flask run --host=0.0.0.0 --port=80