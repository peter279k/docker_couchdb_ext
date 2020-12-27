# docker_couchdb_ext
![Docker couchdb_ext CI build](https://github.com/peter279k/docker_couchdb_ext/workflows/Docker%20couchdb_ext%20CI%20build/badge.svg?branch=master)

## Introduction

This is the Docker image build environment for PHP with [couchdb_ext repository](https://github.com/ace411/couchdb_ext).

## Usage

The Docker image has been published on Docker hub.

These Docker image registries are as follows:

- [docker_couchdb_ext72](https://hub.docker.com/r/peter279k/docker_couchdb_ext72)
- [docker_couchdb_ext73](https://hub.docker.com/r/peter279k/docker_couchdb_ext73)
- [docker_couchdb_ext74](https://hub.docker.com/r/peter279k/docker_couchdb_ext74)

It can use following command to download Docker image.

```BASH
# Download couchDB extension with PHP 7.2
docker pull peter279k/docker_couchdb_ext72:latest

# Download couchDB extension with PHP 7.3
docker pull peter279k/docker_couchdb_ext73:latest

# Download couchDB extension with PHP 7.4
docker pull peter279k/docker_couchdb_ext74:latest
```

## Docker image build

Of course, it also allows to let developers build Docker image manually:

```BASH
# Build couchDB extension with PHP 7.2
docker build -f Dockerfile72 -t docker_couchdb_ext72 .

# Build couchDB extension with PHP 7.3
docker build -f Dockerfile73 -t docker_couchdb_ext73 .

# Build couchDB extension with PHP 7.4
docker build -f Dockerfile73 -t docker_couchdb_ext74 .
```
