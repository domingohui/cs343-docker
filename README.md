# CS343 Docker Setup

This is a quick setup for compiling and running CS343 code on Windows or macOS using Docker.

Note that this setup is for the Fall 2018 session of CS343. It may need to be modified for later sessions.

### Setup
First, make sure you have [docker](https://www.docker.com/) installed!

```
docker build --tag=cs343 .
./run_cs343_image.sh
```

### Usage
Almost everything should be setup already, you can compile u++ code with the `u++` command. Note that the Ubuntu docker image is pretty bare, if you need additional packages installed you will probably need to install them yourself.
