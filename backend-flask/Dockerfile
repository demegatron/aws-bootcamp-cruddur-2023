FROM python:3.10-slim-buster
 
# Inside Container
# Make a new folder inside container  
WORKDIR /backend-flask

# Outside Container -> Inside Container
# This contains the libraries we want to install to run the app
COPY requirements.txt requirements.txt

# Inside Container
# Install the python libraries used for the app
RUN pip3 install -r requirements.txt

# . Means everything in the current directory
# First period . - /backend-flask (outside container)
# Second period . - /backend-flask (inside container)
COPY . .

# Set Envrionment variables (En Vars)
# Inside the container and will remain set when the container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}


# CMD (Command)
# python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]