# About this Repo

[![Build Status](https://github.com/yevgen4989/base-php/workflows/Build%20docker%20image/badge.svg)](https://github.com/yevgen4989/base-php/actions)
[![Docker Pulls](https://img.shields.io/docker/pulls/yevgen4989/base-php.svg)](https://hub.docker.com/r/yevgen4989/base-php)
[![Docker Stars](https://img.shields.io/docker/stars/yevgen4989/base-php.svg)](https://hub.docker.com/r/yevgen4989/base-php)
[![Docker Layers](https://images.microbadger.com/badges/image/yevgen4989/base-php.svg)](https://microbadger.com/images/yevgen4989/base-php)

This repository is a fork of https://github.com/docker-library/php with a few changes:

* We build only Alpine-based FPM variants
* All images based on [alpine](https://github.com/yevgen4989/alpine) 3.13 version due to [this](https://github.com/alpinelinux/docker-alpine/issues/182) change in 3.14 that prevents us from running it on older docker versions

## Docker Images

* All images based on Alpine Linux
* Base image: [yevgen4989/alpine](https://github.com/yevgen4989/alpine)
* [Docker Hub](https://hub.docker.com/r/yevgen4989/base-php)

Supported tags and respective `Dockerfile` links:

* `8.1.2`, `8.1`, `8`, `latest` [_(Dockerfile)_](https://github.com/yevgen4989/base-php/tree/master/8.1/alpine3.15/fpm/Dockerfile.super)
* `8.0.15`, `8.0` [_(Dockerfile)_](https://github.com/yevgen4989/base-php/tree/master/8.0/alpine3.15/fpm/Dockerfile.super)
* `7.4.27`, `7.4`, `7` [_(Dockerfile)_](https://github.com/yevgen4989/base-php/tree/master/7.3/alpine3.15/fpm/Dockerfile.super)
* `7.3.33`, `7.3` [_(Dockerfile)_](https://github.com/yevgen4989/base-php/tree/master/7.3/alpine3.15/fpm/Dockerfile.super)

All images built for `linux/amd64` and `linux/arm64`
