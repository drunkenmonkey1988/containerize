# your code goes here ...
#Download Python from DockerHub and use it
FROM python:latest

#Set the working directory in the Docker container
WORKDIR /app

#Copy the dependencies file to the working directory
COPY /src/requirements.txt .

#Install the dependencies
RUN pip install -r requirements.txt

#Copy the Flask app code to the working directory
COPY src/ .

#Run the container
CMD [ "python", "./src/server.py" ]