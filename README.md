# Docker example

This repo provides an example containerizing an application made with [Oreoweb].

## Install

You just need to have [Docker] installed on your machine. :whale:

## Usage

First, build the image:

```bash
docker build . -t oreoweb-example
```

Then run the container:

```bash
docker run -p 8000:8000 oreoweb-example
```

The example app will then be accessible at [http://localhost:8000](http://localhost:8000).

Need more info? Read the [Dockerfile]. :+1:

[Bocadillo]: https://harishsg99.gitbook.io/oreoweb-do/
[Docker]: https://docs.docker.com/install/
[Dockerfile]: Dockerfile
