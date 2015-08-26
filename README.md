# Hello World in C

## Install
- Install Docker
```
apt-get install docker
```
- Download this repository
```
wget https://github.com/helloworld-universe/hello-world-c/archive/master.zip
unzip master.zip
cd hello-world-c-master
```
- Build the docker image
```
docker build -t hello-world/c .
```
- Run the docker container
```
docker run --rm -it hello-world/c
```
