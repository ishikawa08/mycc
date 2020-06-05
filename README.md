# C lang Compiler

My C language compiler

## Docker

This works on Docker.

### Build docker

`docker build --force-rm=true -t c_compiler .`

### Run Docker

`docker run --rm -v $HOME/[hoge]/mycc:/mycc -w /mycc c_compiler [make]`

### Remove docker container

`docker ps -a`

`docker rm -f [CONTAINER ID]`

### Remove docker image

`docker images`

`docker rmi -f [IMAGE ID]`


## Make commands

### make
`make`

### Run unit test:
`make test`

