# ruby-node-alpine

This docker image provides Ruby, Node, and Yarn.
It is intended to be used for a Rails app environment
that supports client-side resources through Rails' Webpacker.

This image is a combination of the following images from Docker Hub:

[2.2.8-alpine](https://github.com/docker-library/ruby/blob/master/2.2/alpine3.4/Dockerfile) from <https://hub.docker.com/_/ruby/>

[8.8.0-alpine](https://github.com/nodejs/docker-node/blob/9eedeaba3b58f15b9ad2eb8035d48c502e868be6/8.8/alpine/Dockerfile) from <https://hub.docker.com/_/node/>

This image provides provides the following library versions by default:

- Ruby (2.2.8)

- Node (8.8.1)

- Yarn (1.2.1)

Based on Alpine v3.4