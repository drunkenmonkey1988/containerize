# your code goes here ...
#Download Python from DockerHub and use it
FROM python:3.7
RUN mkdir /usr/src/app/
WORKDIR /usr/src/app/
EXPOSE 80
EXPOSE 443
COPY . /usr/src/app/
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD [ "python", "./app/src/server.py" ]