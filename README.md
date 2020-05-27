# My C Compiler

C langage compiler

## Docker

This works on Docker.

Build docker
`docker build --force-rm=true -t c_compiler .`

Removing docker container
`docker rm -f [CONTAINER ID]`

Removing docker image
`docker rmi -f [IMAGE ID]`

Running
`docker run --rm -v $HOME/[hoge]/mycc:/mycc -w /mycc c_compiler [make]`

## Build
Run making to build:
`make`

Run unit test:
`make test`

