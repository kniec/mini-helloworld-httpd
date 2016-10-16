# mini-helloworld-httpd

A 11.68 kB 'Hello World' docker container, written in C and compiled statically with musl. Code stolen from [Rosetta Code](https://rosettacode.org/wiki/Hello_world/Web_server#C)

```
$ docker images | grep mini-httpd
mini-httpd                                       latest              45375b4d6e02        About a minute ago   11.68 kB
```

## Requirements

  * docker
  * musl
  * gcc
  * sstrip
  * upx

## Running

```
make run
```

The server will be available on port 8080.
