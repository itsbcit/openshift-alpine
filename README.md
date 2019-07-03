# openshift-alpine
[![Build Status](https://travis-ci.org/itsbcit/openshift-alpine.svg?branch=master)](https://travis-ci.org/itsbcit/openshift-alpine)
Alpine Linux Docker image with OpenShift shims

## Supported Tags
* [`3.9, latest`](https://github.com/itsbcit/openshift-alpine/blob/master/3.9/Dockerfile)
* [`3.8`](https://github.com/itsbcit/openshift-alpine/blob/master/3.8/Dockerfile)
* [`3.9-supervisord`](https://github.com/itsbcit/openshift-alpine/blob/master/3.9-supervisord/Dockerfile)
* [`3.8-supervisord`](https://github.com/itsbcit/openshift-alpine/blob/master/3.8-supervisord/Dockerfile)

## supervisord version
[http://supervisord.org/configuration.html]()

`COPY your-supervisor.conf /etc/supervisor/conf.d/`
