
# Run following command on terminal

docker build --tag=101272540_hello_docker .

docker image ls

docker run -p 4000:80 101272540_hello_docker

docker container stop CONTAINER_ID

docker container ls