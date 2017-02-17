[![Build Status](https://travis-ci.org/elastic/beats-docker.svg?branch=master)](https://travis-ci.org/elastic/beats-docker)

## Description

This repository contains the official [Beats][beats] Docker images from
[Elastic][elastic].

These images are currently under development, and should be considered alpha-quality.

Please do not run these images in production, but feel free to experiment.

[beats]: https://www.elastic.co/products/beats
[elastic]: https://www.elastic.co/

## Supported Docker versions

The images have been tested on Docker 1.13.1.

## Contributing, issues and testing

Acceptance tests for the image are located in the `test` directory, and can
be invoked with `make test`. Python 3.5 and virtualenv are required to run
the tests.

This image is built on [Ubuntu 16.04][ubuntu-1604].

[ubuntu-1604]: https://github.com/tianon/docker-brew-ubuntu-core/blob/188bcceb999c0c465b3053efefd4e1a03d3fc47e/xenial/Dockerfile