# docker-webssh - ARM64V8
Run webssh in docker, version arm64v8 (raspberry)

## [docker](http://www.docker.com)
Don't know? I am pretty sure this project is not what you are looking for. Just skip it. 
Honestly, I am also studying it, can not say much but really a cool tool you will like. Don't hesitate to try it!

## [webssh](https://github.com/huashengdun/webssh)
A simple web SSH client. Written in Python.


## How to use
To start a container from this image:



``` bash
$ git clone https://github.com/GustavoMotaDF/docker-webssh-arm64v8.git

$ cd docker-webssh

$ docker build -t snsyzb/webssh-arm64v8 .

$ docker run -d --name webssh -p 8080:8080 snsyzb/webssh-arm64v8
```
The container will start a web application on 8080 port, so you can visit your own ssh client web application via openning localhost:8080 in your browser.
