# Flask-Docker-App

## Instructions

1. Add a Dockerfile folder to this project
1. Find out how a Dockerfile should look like for a python project online
1. Successfully run this python app

END

docker build -t "flask_app" .
docker run -d -p 5050:5000 --name "container_flask_app" flask_app
