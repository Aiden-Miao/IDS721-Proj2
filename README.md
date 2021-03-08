This is a Docker container project that will simply return 'hello world'

## Docker build
docker build --tag aidenmiao/ids721-proj2:latest .

## Docker image list
docker image ls

## Run the container
docker run -it aidenmiao/ids721-proj2:latest python app.py

## Push to dockerhub
./push_docker.sh

## Run the docker image remotely 
docker pull aidenmiao/ids721-proj2:latest
docker run -it aidenmiao/ids721-proj2:latest python app.py
