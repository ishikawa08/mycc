# My C Compiler

C langage compiler

## Docker

This works on Docker.

`docker build -t c_compiler`

`docker run --rm -v $HOME/hoge/mycc:/mycc -w /mycc c_compiler make`

## Build
Run make to build:
`make`

unit test:
`make test`

