# grafana-docker
Grafana stack shipped on Docker

## Run
To start the stack:

mkdir -p grafana-data
mkdir -p prometheus-data
export USERIDS=$(id -u):$(id -g)
docker-compose up -d
